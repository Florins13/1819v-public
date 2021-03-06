# Outline and resources #

## Week 1
### 18/02/2019 - Course introduction
* Syllabus, teaching methodology and bibliography.
  * [Evaluation](https://github.com/isel-leic-daw/1819v-public/wiki/evaluation)
  * [Resources](https://github.com/isel-leic-daw/1819v-public/wiki/resources)

### 20/02/2019 - Designing Web APIs: Introduction
* Web APIs (or HTTP APIs): Concept and Motivation
* The [Architecture of the World Wide Web](https://www.w3.org/TR/webarch/)
* The HTTP protocol: Introduction
* Documentation:
  * ["Introduction to Web APIs"](https://github.com/isel-leic-daw/1819v-public/wiki/Web-APIs)
  * ["Designing evolvable Web APIs: Chapter 1"](https://www.oreilly.com/library/view/designing-evolvable-web/9781449337919/ch01.html)

## Week 2
### 25/02/2019 - Software design considerations
* Dependency Injection (DI): Motivation and consequences
  * Through construction parameters
  * Done explicitely by a wiring up procedure that constructs the solution's object graph 
* Materialization of the discussed principles on the HVAC controller application, developed during the classes
* DI containers: [Spring](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#spring-core)
  * Motivation
  * Using Spring through [Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
  * [Spring Initializr](https://start.spring.io/)
* Refactoring the HVAC controller application to use Spring Boot

### 27/02/2019 - Designing Web APIs: Revisited
* Goal: Creating a Web API for the HVAC controller application
* The HTTP protocol, revisited
  * Request-response message exchange semantics and pattern
  * Request methods [semantics](https://tools.ietf.org/html/rfc7231#section-4.3) and [properties](https://tools.ietf.org/html/rfc7231#section-4.2)
  * Response status code [semantics](https://tools.ietf.org/html/rfc7231#section-6)
  * ["HTTP Method selection"](https://github.com/isel-leic-daw/1819v-public/wiki/HTTP-method-selection)
* Documentation:
  * ["Designing evolvable Web APIs: Chapter 2"](https://www.oreilly.com/library/view/designing-evolvable-web/9781449337919/ch02.html)

## Week 3
### 4/03/2019 - Designing Web APIs: Continued
* Goal: Maturing the HVAC Web API up to RMM Level 2
  * On class implementation
* The [Spring Web MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html) framework
  * Motivation
  * Architecture 
  * Threading model
* Documentation
  * [HTTP Status Code registry](http://www.iana.org/assignments/http-status-codes/http-status-codes.xhtml)
  * ["How to Think About HTTP Status Codes"](https://www.mnot.net/blog/2017/05/11/status_codes)
  * ["How to fail in HTTP APIs"](https://github.com/isel-leic-daw/1819v-public/wiki/How-to-fail-in-HTTP-APIs)

### 6/03/2019 - Resources vs External Representations: Introduction
* The concept of a Resource in a Web API
  * Motivation 
  * Resource identification through URIs
* Introduction to representation formats, evolvability, and hypermedia
* Documentation:
  * ["Designing evolvable Web APIs: Chapter 5"](https://www.oreilly.com/library/view/designing-evolvable-web/9781449337919/ch05.html)

## Week 4
### 11/02/2019 - Practical class
* Project phase 1 - Design of the HTTP-based API 
### 13/02/2019 - Designing Web APIs: External Representations
* Goal: Moving HVAC Web API towards RMM Level 3
* Representation design, hypermedia and web linking
  * [Web Linking](https://tools.ietf.org/html/rfc5988)
  * [HAL-Hypermedia Application Language](https://tools.ietf.org/html/draft-kelly-json-hal-08)
  * [HAL-forms](https://rwcbook.github.io/hal-forms/)
  * [Collection+JSON](http://amundsen.com/media-types/collection/)
* Documentation:
  * ["Designing evolvable Web APIs: Chapter 6"](https://www.oreilly.com/library/view/designing-evolvable-web/9781449337919/ch06.html)
* For reference:
  * [IANA Link Relations Registry](https://www.iana.org/assignments/link-relations/link-relations.xhtml)
  * [IANA Media Types Registry](https://www.iana.org/assignments/media-types/media-types.xhtml)

## Week 5
### 18/02/2019 - Practical class
* Project phase 1 - Design of the HTTP-based API 
### 20/02/2019 - Designing Web APIs: External Representations (Continued)
* Goal: Moving HVAC Web API towards RMM Level 3 (continued)
* Representation design, hypermedia and web linking (revisited)
  * An example: [Amazon API gateway](https://docs.aws.amazon.com/apigateway/api-reference/)
  * Representation of domain specific link relations 
  * Error representation with [Problem-Json](https://tools.ietf.org/html/rfc7807)
* [Exception handling in Spring MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html#mvc-ann-exceptionhandler)

## Week 6

## Week 7

## Week 8

## Week 9

## Week 10

## Week 11

## Week 12

## Week 13

## Week 14

## Week 15
