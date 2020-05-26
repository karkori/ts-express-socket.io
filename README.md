# WebSocket API with Express Typescript
> A boilerplate to develop realtime and event-based API to perform **broadcasting** and **real-time data transfer** with Socket.io on Express written in TypeScript and Redis. 

***

Table Of Contents 
=================

  * [About The Project](#about-the-project)
  * [Technical Discussion](#technical-discussion)
  * [Getting Started](#getting-started)
    * [Installation](#installation)
  * [Tools and Technologies](#tool-and-technologies)
  * [About](#about)
    * [Author](#author)
    * [License](#license)

***

About The Project
=================
The project focus on implementation of Socket.io Server's library features to develop an **independent, maintainable and deployable** bidirectional communication microservices secured with OAuth 2.0 authorization protocol. The services **provide backend APIs** for other services from different projects to emit or broadcast their data to the mentioned clients and **allow desktop browser, mobile browser or native mobile application to listen on the socket** to receive the emitted data based on events or connection. 

*** 

Motivation
==========
In software development process, several projects may required to perform broadcasting or real time data transfer with WebSocket module. However, it's pretty time and resource consuming for an organization to allow various team to research and develop their own WebSocket module. 

Therefore, a Socket API microservices is developed and maintain independently to enabled multiple teams or project to make use of a single service managed by small team of developers with exclusive knowledge on WebSocket. 

*** 

Technical Discussion
====================

The project is designed with three-tiers architecture and coherent with SOLID principle to establish a maintainable and extensible codebase for perfective and corrective maintenance.

OAuth 2.0 security protocol with password grant is selected to prevent unauthorized access onto the APIs and listen to the Socket.io's URL protocol. The services required public key provided from authorization server to verify the *Signature of Tokens* given by Client or Resource Owner. 

Typescript programming language with ES6 features or above is used to develop the project to increase greater discipline to saturate the codebase with strict type checking, better code structuring and object-oriented programming techniques. 

Docker Compose is use for define and running both Express Server and Redis in-memory database containers to build the service. The compose file consists of development and production version for developers help improve compatibility and standardization of development, staging and production environment.





