# 2025-11-05

[meetup.com](https://www.meetup.com/berner-go-meetup/events/310847050)

## Abusing Container Registries to Build Self-Updating Go Binaries - Christian Blättler

Container registries aren't just for Docker images. Using ORAS, we can stuff Go binaries into OCI-compliant registries and build programs that check for updates, download new versions, and replace themselves at runtime. This talk walks through the implementation details: querying registry APIs for new tags, handling the binary swap dance, and building in rollback logic when the new version inevitably breaks something. You'll see how to turn any container registry into a binary distribution system and why this approach beats rolling your own update infrastructure.

Links: [Slides]()  
Speaker: [GitHub](https://github.com/cblaettl) | [LinkedIn](https://www.linkedin.com/in/cblaettl/)

## From Go to the Browser: Parsing GoPro Metadata with WebAssembly - Chrigu Cueni

I’ve been working on a side project called TrailTrace. The core is written in Go, where I parse GoPro video metadata (GPS, gyro, accelerometer, etc.). To make it run in the browser, the Go code is compiled to WebAssembly, so the same parsing logic works directly client-side without a backend. The frontend is a Nuxt app that visualizes rides or ski tours on a map.One of the interesting parts has been dealing with memory: One can use memory in JS freely, but WebAssembly itself is limited in memory, so I had to find ways to stream large video files efficiently without hitting that limit.
If you’re curious, you can try a demo here: [https://trailtrace.video](https://trailtrace.video)

Links: [Slides](https://gamma.app/docs/And-now-for-something-completely-different-u51bgypt3fqib3u) | [Code](https://github.com/chrigu/go-gpmf)  
Speaker: [GitHub](https://github.com/chrigu) | [LinkedIn](https://www.linkedin.com/in/christiancueni/)

## Acceptance Testing a Terraform Provider for Incus - Fabian Mettler

Terraform providers let us manage infrastructure by bridging Terraform Core with external APIs. But how do you make sure your provider actually works as expected? In this talk, I’ll walk through how to write acceptance tests for a Terraform provider, using the Incus provider as an example. Incus is a modern, secure, and powerful system container and virtual machine manager. You’ll see how acceptance tests spin up real Terraform runs, verify resource lifecycles, and ensure the provider stays reliable as both Terraform and Incus evolve.

Links: [Slides]() | [Code](https://github.com/lxc/terraform-provider-incus)  
Speaker: [GitHub](https://github.com/maveonair) | [LinkedIn](https://www.linkedin.com/in/fabian-mettler-114969101/)
