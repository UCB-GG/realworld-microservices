![Build Status](https://travis-ci.com/profjordanov/realworld-microservices.svg?branch=master)

# ![RealWorld Example App](logo.png)

> ### A Microservices ASP.NET Core codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.


### [RealWorld Repo](https://github.com/gothinkster/realworld)


This codebase was created to demonstrate a fully-fledged, micro-service architecture built with **ASP.NET Core**. It includes gRPC, Domain-Driven Design, CQRS, Mediator, Proxy, and many more patterns.

It completely adheres to the **ASP.NET Core** community style guides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.

# Features

- [x] Microservices architecture - architectural style that provides a highly maintainable, testable, loosely coupled collection of services that are independently deployable and organized around business capabilities. Service layer is placed on top of te Domain Models. 

- [x] Communication via gRPC - a new, growing way to connect services in a cross-platform, cross-language way. 

- [x] Remote Proxy - acts like a local resource while hiding the details of how to connect to a remote resource over a network. It behaves as API gateway between the client and services.
