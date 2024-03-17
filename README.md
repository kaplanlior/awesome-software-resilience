# awesome-software-resilience
Curated list of software resilience libraries and clients, making your application more robust while consuming 3rd party API &amp; services

## Libraries

### C#
[Polly](https://github.com/App-vNext/Polly) ![Stars](https://img.shields.io/github/stars/App-vNext/Polly) ![GitHub Latest Release)](https://img.shields.io/github/v/release/App-vNext/Polly?logo=github) <br>
Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

### Go
[Backoff](https://github.com/cenkalti/backoff) ![Stars](https://img.shields.io/github/stars/cenkalti/backoff) ![GitHub Latest Release)](https://img.shields.io/github/v/tag/cenkalti/backoff?logo=github) <br>
Backoff is an exponential backoff algorithm in Go 

[gobreaker](https://github.com/sony/gobreaker) ![Stars](https://img.shields.io/github/stars/sony/gobreaker) ![GitHub Latest Release)](https://img.shields.io/github/v/tag/sony/gobreaker?logo=github) <br>
gobreaker is a circuit Breaker implemented in Go

[go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware) ![Stars](https://img.shields.io/github/stars/grpc-ecosystem/go-grpc-middleware) ![GitHub Latest Release)](https://img.shields.io/github/v/release/eapache/go-resiliency?logo=github) <br>
go-grpc-middleware has support for interceptor chaining, auth, logging, retries and more. 

[go-resiliency](https://github.com/eapache/go-resiliency) ![Stars](https://img.shields.io/github/stars/eapache/go-resiliency) ![GitHub Latest Release)](https://img.shields.io/github/v/release/eapache/go-resiliency?logo=github) <br>
go-resiliency has Resiliency patterns for golang. Based in part on Hystrix, Semian, and others.

[go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) ![Stars](https://img.shields.io/github/stars/hashicorp/go-retryablehttp) ![GitHub Latest Release)](https://img.shields.io/github/v/tag/hashicorp/go-retryablehttp?logo=github) <br>
go-retryablehttp provides a familiar HTTP client interface with automatic retries and exponential backoff.

[retry-go](https://github.com/avast/retry-go) ![Stars](https://img.shields.io/github/stars/avast/retry-go) ![GitHub Latest Release)](https://img.shields.io/github/v/release/avast/retry-go?logo=github) <br>
Retry-go is a simple library for retry mechanism.


### Java
[failsafe](https://github.com/failsafe-lib/failsafe) ![Stars](https://img.shields.io/github/stars/failsafe-lib/failsafe) <br>
Failsafe is a Fault tolerance and resilience patterns for the JVM. Failsafe is a lightweight, zero-dependency library for handling failures in Java 8+. It has a concise API for handling everyday use cases and the flexibility to handle everything else. Failsafe works by wrapping executable logic with one or more resilience policies, which can be combined and composed as needed.

[resilience4j](https://github.com/resilience4j/resilience4j) ![Stars](https://img.shields.io/github/stars/resilience4j/resilience4j) ![GitHub Latest Release)](https://img.shields.io/github/v/release/resilience4j/resilience4j?logo=github) <br>
Resilience4j is a fault tolerance library designed for Java8 and functional programming.

[spring-retry](https://github.com/spring-projects/spring-retry) ![Stars](https://img.shields.io/github/stars/spring-projects/spring-retry) ![GitHub Latest Release)](https://img.shields.io/github/v/release/spring-projects/spring-retry?logo=github) <br>
Spring-retry provides declarative retry support for Spring applications. It is used in Spring Batch, Spring Integration, and others. Imperative retry is also supported for explicit usage.

### JavaScript
[async-retry](https://github.com/vercel/async-retry) ![Stars](https://img.shields.io/github/stars/vercel/async-retry) ![GitHub Latest Release)](https://img.shields.io/github/v/release/vercel/async-retry?logo=github) <br>
async-retry aim for retrying made simple, easy, and async.

[Opossum](https://github.com/nodeshift/opossum) ![Stars](https://img.shields.io/github/stars/nodeshift/opossum) ![GitHub Latest Release)](https://img.shields.io/github/v/release/nodeshift/opossum?logo=github) <br>
Opossum is a Node.js circuit breaker that executes asynchronous functions and monitors their execution status. When things start failing, opossum plays dead and fails fast. If you want, you can provide a fallback function to be executed when in the failure state.


### Python
[Backoff](https://github.com/litl/backoff) ![Stars](https://img.shields.io/github/stars/litl/backoff) ![GitHub Latest Release)](https://img.shields.io/github/v/tag/litl/backoff?logo=github) <br>
Backoff is a Python library providing function decorators for configurable backoff and retry 

[Tenacity](https://github.com/jd/tenacity) ![Stars](https://img.shields.io/github/stars/jd/tenacity) ![GitHub Latest Release)](https://img.shields.io/github/v/tag/jd/tenacity?logo=github) <br>
Tenacity is a retrying library for Python.

### Ruby
[Semian](https://github.com/Shopify/semian) ![Stars](https://img.shields.io/github/stars/Shopify/semian) ![GitHub Latest Release)](https://img.shields.io/github/v/release/Shopify/semian?logo=github) <br>
semian is a Resiliency toolkit for Ruby for failing fast

### TypeScript
[axios-retry](https://github.com/softonic/axios-retry) ![Stars](https://img.shields.io/github/stars/softonic/axios-retry) ![GitHub Latest Release)](https://img.shields.io/github/v/release/connor4312/cockatiel?logo=github) <br>
axios-retry is an Axios plugin that intercepts failed requests and retries them whenever possible.

[Cockatiel](https://github.com/connor4312/cockatiel) ![Stars](https://img.shields.io/github/stars/connor4312/cockatiel) ![GitHub Latest Release)](https://img.shields.io/github/v/release/connor4312/cockatiel?logo=github) <br>
Cockatiel is a resilience and transient-fault-handling library that allows developers to express policies such as Backoff, Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback. Inspired by .NET Polly

## Tools / Clients

