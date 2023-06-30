# 2023-03-21

[meetup.com](https://www.meetup.com/de-DE/berner-go-meetup/events/291290566/)

## Zero-effort type-safe parsing of JSON and XML – Tom Payne

Need to get JSON or XML data into your program quickly but don't want to lose type safety? Have a bunch of JSON objects with no schema? Have a 100,000-line XML document with elements nested deeper than the Mariana trench? Trying to escape NodeJS/MongoDB document database hell?
In this practical-focused talk, I'll introduce two tools that allow you to generate Go structs from arbitrary JSON and XML documents with a single command. We'll see how to use them, and dig a little deeper to learn how they generate schemas from multiple input documents.

Links: [go-jsonstruct](https://github.com/twpayne/go-jsonstruct) | [go-xmlstruct](https://github.com/twpayne/go-xmlstruct)  
Speaker: [Github](https://github.com/twpayne)

## Go Performance Profiling – Florian Lehner

Often there are multiple ways to solve a given task in Go. Profiling these solutions can help to decide which solution performs best for the given task. In this talk we look into different ways to profile Go executables using Go internal tooling, system performance tooling and eBPF.

Links: [Slides](https://github.com/florianl/talks/blob/master/2022-zrh-goperf.pdf)  
Speaker: [Github](https://github.com/florianl) | [Twitter](https://twitter.com/0x0F10) | [LinkedIn](https://www.linkedin.com/in/florian-lehner/)

## Does Bazel make sense for my Go code – Patrick Fiaux

Bazel is a polyglot build systems from google, the tagline claims "{ Fast, Correct } — Choose two". Is this true for Go as well? When does it make sense to introduce Bazel? What does it look like if we do?

Links: [Slides](pfiaux_bazel_barnergo20231.pdf)  
Speaker: [Github](https://github.com/pfiaux) | [Twitter](https://twitter.com/swisspaaat) | [LinkedIn](https://ch.linkedin.com/in/patrickfiaux)
