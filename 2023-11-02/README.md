# 2023-11-02

[meetup.com](https://www.meetup.com/de-DE/berner-go-meetup/events/293782118/)

## Assumptions and mistakes - developing and refactoring the operations management tool Mule – Rene Zbinden, Marc Sauter

In 2016, PostFinance once again developed a new operations management tool - this time in Go. There were already a few predecessors written in C, Perl, TCL and Java which were more or less used and appreciated. At that time, Go was no longer new, but it wasn’t the well-known «Java» either, which is why there were some critical voices about this project as well. In addition, Mule was not developed by a well-rehearsed development team, but by a mix of infrastructure and operations members. The first version succeeded, was accepted, and appreciated. With the spread of the tool, problems with the used technologies became visible and tangible. Five years after starting the project, Mule finally underwent a complex refactoring, and the result is quite impressive.

## gRPC retry mechanisms with go - Thomas Gosteli

gRPC is a high performance, open source universal RPC (remote procedure call) framework (<https://grpc.io/>) with support for various languages and with a wide variety of features. One of these features is client side retries. These retries are disabled by default and must be configured using so called [service configs](https://github.com/grpc/grpc/blob/master/doc/service_config.md). In this talk I’ll give you a short intro to gRPC with go, some insights about these automatic retry capabilities, how to configure them and where the limit of the retry feature is.

Links: [Slides](ghouscht_gRPC_retry_mechanisms_with_go.pdf) | [Repo](https://github.com/ghouscht/gRPC-retry-mechanisms-with-go/)  
Speaker: [Github](https://github.com/ghouscht) | [Twitter](https://twitter.com/ghouscht) | [LinkedIn](http://www.linkedin.com/in/thomas-gosteli-776b0a299)

## Extendable Applications in Go - Philip Sahli

Drawing from my experience with extensible projects like Terraform, I'll introduce the concept of "plugins" in Golang. By focusing on HashiCorp's widely utilized implementation, I'll showcase how plugins enhance software extendability. Join me in exploring how HashiCorp's plugin framework is revolutionizing application development.

Links: [Slides](https://www.slideshare.net/philipsahli/extendable-applications-in-go)  
Speaker: [Github](https://github.com/philipsahli) | [LinkedIn](https://www.linkedin.com/in/philipsahli)

## Dr. Golove - or How I Learned to Stop Worrying and Love //go:generate – John M. Hutchison

John will share his personal journey from skepticism towards code generation to acceptance and learning to love //go:generate as an invaluable tool. Thoughts on and about code generation with some small examples of what lead to a change of heart.

Links: [Slides](#)  
Speaker: [Github](https://github.com/cldmstr) | [Twitter](https://twitter.com/jackharbinger) | [LinkedIn](https://ch.linkedin.com/in/john-m-hutchison)
