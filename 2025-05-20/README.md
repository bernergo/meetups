# Bärner Go 2025 no. 2 Special Format: Live Code Reviews

This page contains relevant links and notes mentioned during the few topics we discussed together.

Do you remember a link/resource that was mentioned and
it's mssing here? Open a pull request to add it please.

## Topic 1: Translation framwork and how to integrate plugins - Roman

- [TOKI tool](https://github.com/romshark/toki)
- [TIK format](https://github.com/romshark/tik)
- [ICU message parsing](https://github.com/romshark/icumsg)
- https://github.com/wasmvision/wasmvision uses wasm plugins approach might be interesting to explore to use sandboxing
- Terraform provides a plugin library they use in various hashicorp tools https://github.com/hashicorp/terraform-plugin-go

## Topic 2: Checking depencencies and handling security issues - Martin

- https://github.com/google/capslock (https://security.googleblog.com/2023/09/capslock-what-is-your-code-really.html)
- open source security foundation OSSF tools:
    - [scorecard.dev](https://scorecard.dev/)
    - [deps.dev](https://deps.dev/)
- https://socket.dev/ "Secure your dependencies. Ship with confidence."
- Kernel level filters/features i.e. [Landlock](https://docs.kernel.org/userspace-api/landlock.html)
- Fake *\_test.go files https://www.arp242.net/jia-tan-go.html

## Topic 3: Middlewares, Routing, Templating and avoiding dependencies - John

- https://github.com/romshark/demo-islands
- [chi middlewares](https://github.com/go-chi/chi/tree/master/middleware)

## Topic 4: Deploying a go binary in a closed ecosystem (i.e. internal tool for other engineers) - Martin

If Brew, NPM, [go releaser](https://goreleaser.com/) or other options are not possible because the tool is not open source.

- Use brew with a private cask
- Use go run (needs go installed)
- Use [ORAs](https://oras.land/) to distribute artifacts using an OCI registry
- Use auto update mechanism in the binary (does not solve initial install)
- Use a Device management solution to push the binary to company machines or make them available as self service install i.e. [JAMF](https://www.jamf.com/)
- Provide the tool in a container and provide a [dev container config](https://containers.dev/)
- Use a [nix](https://nixos.org) package
- Use Github [gh cli extensions](https://docs.github.com/en/github-cli/github-cli/using-github-cli-extensions) to install the tools
- Use [Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers) and run the tool within