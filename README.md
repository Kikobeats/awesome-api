# Awesome API [![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for design and implement RESTful APIs.

## Design

### Overview

> REST allows us to create services and applications that can be used by any device or client who understands HTTP.

* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api) [[spanish version](https://elbauldelprogramador.com/buenas-practicas-para-el-diseno-de-una-api-restful-pragmatica/)].
* [gov.uk API technical and data standards](https://www.gov.uk/guidance/gds-api-technical-and-data-standards)
* [Heroku API Reference](https://devcenter.heroku.com/articles/platform-api-reference).
* [How to (and how not to) design REST APIs](https://github.com/stickfigure/blog/wiki/How-to-%28and-how-not-to%29-design-REST-APIs)
* [HTTP API Design by Heroku](https://github.com/interagent/http-api-design).
* [IBM Watson REST API Guidelines](https://github.com/watson-developer-cloud/api-guidelines).
* [Ideal REST API Design](https://betimdrenica.wordpress.com/2015/03/09/ideal-rest-api-design/).
* [Learn REST: A RESTful Tutorial](http://www.restapitutorial.com).
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines).
* [StackOverflow best REST API Design](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/).
* [Zalando RESTful API and Event Scheme Guidelines](http://zalando.github.io/restful-api-guidelines/)

### Status Code

> When you are using a REST design you have to provide the HTTP status code that are the more appropriated to respond to the request.

* [HTTP Status code table in RESTAPITutorial](http://www.restapitutorial.com/httpstatuscodes.html).
* [Status code definition in W3C](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html).

### Authentication

* [Authentication Cheat Sheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet).
* [Web Authentication Methods Explained](https://blog.risingstack.com/web-authentication-methods-explained/).

#### JWT

> JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.

* [Guide on API authentication and authorization](https://www.moesif.com/blog/technical/restful-apis/Authorization-on-RESTful-APIs/).
* [JWT Draft in IETF](https://tools.ietf.org/html/draft-ietf-oauth-json-web-token).
* [JWT.io](http://jwt.io/).
* [Using JSON Web Tokens as API Keys](https://auth0.com/blog/2014/12/02/using-json-web-tokens-as-api-keys/).

## Caching

* [Caching best practices & max-age gotchas](https://jakearchibald.com/2016/caching-best-practices/).
* [Increasing Application Performance with HTTP Cache Headers](https://devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers).

## Security

* [APISecurityBestPractices](https://github.com/GitGuardian/APISecurityBestPractices).
* [Helmet, help secure Express/Connect apps with various HTTP headers](https://www.npmjs.com/package/helmet).
* [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist/).

## Format

* [HAL](http://stateless.co/hal_specification.html) – Simple format that gives a consistent and easy way to hyperlink between resources in your API (see: [HATEOAS](#hateoas)).
* [Hydra](http://www.hydra-cg.com/) – Vocabulary for Hypermedia-Driven Web APIs (W3C).
* [JSend](http://labs.omniti.com/labs/jsend) – Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
* [JSON API](http://jsonapi.org/) – Standard for building APIs in JSON.
* [JSON-LD](http://json-ld.org/) – Standard for describing Linked Data and hypermedia relations in JSON (W3C).
* [OData](http://www.odata.org/) – Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [RAML](http://raml.org/) – Simple and succinct way to describe RESTful API.
* [Schema.org](http://schema.org) – Collection of schemas describing common data models.

## Discover

> Need a API for your projects?

### Curated list

* [Awesome APIs Directory](https://github.com/Abhishaker17/Awesome-APIs) – A public list of APIs from round the web.
* [Free LLM API Hub](https://github.com/pacocartones/free-llm-api-hub) – A verified list of free-tier LLM APIs from 60+ providers, with a no-auth JSON API.
* [public apis](https://github.com/toddmotto/public-apis) – A collective list of public JSON APIs for use in web development.

### Directory

* [apis.io](http://apis.io) – API Search service to help discover APIs on the web.

### Querying

* [Bruno](https://github.com/usebruno/bruno) - Opensource IDE for exploring and testing APIs.
* [httpie](https://github.com/jkbrzt/httpie) – Command line HTTP client, far more dev-friendly than `curl`.
* [Insomina](https://insomnia.rest/) – A Fancy HTTP REST Client.
* [jq](https://github.com/stedolan/jq) – Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
* [resty](https://github.com/micha/resty) – Little command line REST client that you can use in pipelines (bash or zsh).

### Mocking

* [Beeceptor](https://beeceptor.com) - Beeceptor helps intercepting API calls and mocking them selectively. Creates an endpoint for wrapping original API and routes requests.
* [FakeRest](https://github.com/marmelab/FakeRest) – Patch XMLHttpRequest to fake a REST API client-side.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) – Free online REST service that you can use whenever you need some fake data.
* [json-server](https://github.com/typicode/json-server) – Get a full fake REST API with zero coding in less than 30 seconds.
* [MockServer](https://www.mock-server.com) - Mocking, debugging proxy and chaos engineering for HTTP, gRPC, GraphQL, LLM, MCP, Kafka, TCP and more; mock APIs, record/replay and inspect traffic, verify requests, and inject chaos. Docker, JAR, Helm.

### Response

* [badssl](https://badssl.com) – Testing clients against bad SSL configs.
* [httpbin](https://httpbin.org) – httpbin(1): HTTP Request & Response Service.

## Documentation

> One of the most important part of your API is have a good documentation and updated with the code.

### Free

* [sourcey](https://sourcey.com/docs).

### Services

* [GitBook](https://www.gitbook.com/).
* [RapidAPI](https://docs.rapidapi.com/docs).
* [Readme.io](https://readme.io/).

## Logging

* [Apitally](https://apitally.io) - Simple, privacy-focused API monitoring, analytics, and request logging.
* [Moesif API Analytics](https://www.moesif.com/features/api-logs). Log and Understand API Traffic.
* [morgan for expressjs](https://github.com/expressjs/morgan).
* [PM2 by keymetrics](https://pm2.keymetrics.io).

## Modeling and SaaS

> Based in DDD (Domain Driven Development). Generates automatically API's in different languages.

* [Alteranatives to API Plug](https://www.producthunt.com/alternatives/api-plug) – 9 alternative and related products to api plug.
* [Apiary](https://apiary.io/) – Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [import.io, turn web pages into Data](https://www.import.io/).
* [RAML, RESTful API Modeling Language](http://raml.org).
* [Runscope](https://www.runscope.com/) – Automated API Monitoring & Testing.
* [swagger.io](http://swagger.io).
* [wrapAPI, Build an API on top of any website](https://wrapapi.com).

## Libraries

> Used it to improve your workflow

* [async-ratelimiter](https://github.com/microlinkhq/async-ratelimiter) – Rate limit made simple, easy, async, backed in Redis.
* [hashids](https://github.com/niieani/hashids.js) – A small JavaScript library to generate YouTube-like ids from numbers.
* [typeid-js](https://github.com/jetify-com/typeid-js) – Type-safe, K-sortable, and globally unique identifiers inspired by Stripe IDs

## Frameworks

> Designed specifically for building RESTful API's Quickly.

* [FastAPI](https://github.com/tiangolo/fastapi).
* [Loopback](http://loopback.io).
* [rest-hapi](https://resthapi.com).
* [Sails.js](http://sailsjs.org).

## Gateways

> Manage API infrastructure concerns such as authentication/authorization, rate limiting, scaling, analytics, etc.

### Open Source / Self-hosted

* [API Umbrella](http://apiumbrella.io/).
* [KrakenD](http://krakend.io).
* [Mashape Kong](https://getkong.org/).
* [Tyk](https://tyk.io/).
* [WSO2 API Manager](http://wso2.com/api-management/try-it/).
