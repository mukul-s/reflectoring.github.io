---
title: Everything you need to know about the Dependency Inversion Principle
categories: [craft]
date: 2020-03-29 06:00:00 +1100
author: mukul
excerpt: "This is a one-stop practical guide to understand and apply the Dependency Inversion Principle, which is one of the SOLID principles."
image:
  auto: TBD
tags: ["Dependency Inversion Principle", "DIP", "SOLID", "Principles of software development"]
---


>A. HIGH-LEVEL MODULES SHOULD NOT DEPEND UPON LOW LEVEL MODULES. BOTH SHOULD DEPEND UPON ABSTRACTIONS.
>
>B. ABSTRACTIONS SHOULD NOT DEPEND UPON DETAILS. DETAILS
SHOULD DEPEND UPON ABSTRACTIONS.

— *Robert Martin, paper "[The Dependency Inversion Principle](https://web.archive.org/web/20110714224327/http://www.objectmentor.com/resources/articles/dip.pdf)"*


Abstraction is the heart of object-oriented design. It allows the client to be unconcerned with the implementation details of functionality. In Java, abstraction is achieved through abstract classes and interfaces. This article explains the idea of the Dependency Inversion Principle, which is the "D" in the [SOLID](https://en.wikipedia.org/wiki/SOLID) principles.

# What is the Dependency Inversion Principle?
The Dependency Inversion Principle (DIP) states that "high-level module should have a convenient abstraction to depend on to which are then enforce by low-level module".
* Meaning of high-level and low-level dependencies


## Reasons to Follow the Dependency Inversion Principle
Let's understand the following benefits of DIP using an example:
* High reusability
* High replaceability
* More robust codebase


## Is the DIP the same as DI or IoC?
No, they are not.  
DI is about wiring, IoC is about direction, and DIP is about shape.

## Different strategies to implement DIP in the codebase
* Using Abstract Factory pattern
* Using Service Locator pattern
* Using Dependency Injection
* Using Strategy pattern


## Code Smells for DIP
* Dependency chain
* Long if/else statement for initialization

## The Dependency Inversion Principle and Other Software Principles
How DIP is a generalization of LSP and OCP
DIP and SDP (Stable Dependency Principle)

## Conclusion


The example code used in this article is available on [GitHub](TBD).