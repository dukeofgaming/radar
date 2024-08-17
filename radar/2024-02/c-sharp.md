---
title: C#
ring: adopt
quadrant: languages-and-frameworks
tags:
 - language
---

Using C# as part of a mainframe modernization project deployed in kubernetes, participated in a hackathon to enable E2E testing by creating a local functional test that bypassed microservices. The result helped us assess the effort for a rearchitecture of the microservices towards simplification to avoid a greater effort that would have been required to do an excessive amount of mocking.

The lesson learned for the project was to design microservices based on scaling requirements and keep them to a minimum, as this resulted in a distributed monolith with too much complexity for single features. Either starting from a monolith and spin-off microservices resulting from data coming from observability or with a cell-based architecture 

This highlighted the importance of designing microservices with simplicity in mind, for example starting with a monolith and evolving microservices based on observability data, or using a cell-based architecture. This resulted in an initiative to collapse the microservices and to approach functional testing through the front-end.