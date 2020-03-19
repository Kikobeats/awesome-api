# Awesome API [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-api/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-api) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> A curated list of awesome resources for design and implement RESTful APIs.

## Design

### Overview

> REST allows us to create services and applications that can be used by any device or client who understands HTTP.

* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api) [[spanish version](https://elbauldelprogramador.com/buenas-practicas-para-el-diseno-de-una-api-restful-pragmatica/)].
* [Ideal REST API Design](https://betimdrenica.wordpress.com/2015/03/09/ideal-rest-api-design/).
* [Heroku API Reference](https://devcenter.heroku.com/articles/platform-api-reference).
* [API Terms Glossary](https://github.com/Mashape/apiglossary).
* [HTTP API Design](https://github.com/interagent/http-api-design) – Guide extracted from work on the Heroku Platform API.
* [Learn REST: A RESTful Tutorial](http://www.restapitutorial.com).
* [RAPIS: A REST API Standard for the 21th century](https://github.com/lambda2/rapis).
* [IBM Watson REST API Guidelines](https://github.com/watson-developer-cloud/api-guidelines).
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines).
* [Zalando RESTful API and Event Scheme Guidelines](http://zalando.github.io/restful-api-guidelines/)
* [gov.uk API technical and data standards](https://www.gov.uk/guidance/gds-api-technical-and-data-standards)

### Status Code

> When you are using a REST design you have to provide the HTTP status code that are the more appropriated to respond to the request.

* [HTTP Status code table in RESTAPITutorial](http://www.restapitutorial.com/httpstatuscodes.html).
* [httpstatuses.com](https://httpstatuses.com/)
* [Status code definition in W3C](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html).

### Authentication

* [Auth Boss](https://github.com/teesloane/Auth-Boss) – Learn about different authentication methodologies on the web.
* [Authentication Cheat Sheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet).
* [The Problem With API Authentication in Express](https://stormpath.com/blog/the-problem-with-api-authentication-in-express/).
* [Web Authentication Methods Explained](https://blog.risingstack.com/web-authentication-methods-explained/).

#### JWT

> JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.

* [10 Things You Should Know about Tokens](https://auth0.com/blog/2014/01/27/ten-things-you-should-know-about-tokens-and-cookies/).
* [Cookies vs Tokens](https://auth0.com/blog/2014/01/07/angularjs-authentication-with-cookies-vs-token/).
* [JWT Draft in IETF](https://tools.ietf.org/html/draft-ietf-oauth-json-web-token).
* [JWT.io](http://jwt.io/).
* [Using JSON Web Tokens as API Keys](https://auth0.com/blog/2014/12/02/using-json-web-tokens-as-api-keys/).
* [Why Meteor doesn't use session cookies](http://info.meteor.com/blog/session-cookies).
* [JWTinspector.io](https://www.jwtinspector.io).

### Authorization

#### OAuth

> An open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications

* [The OAuth Bible by Mashape](http://oauthbible.com/).

## Caching

* [Caching best practices & max-age gotchas](https://jakearchibald.com/2016/caching-best-practices/).
* [Increasing Application Performance with HTTP Cache Headers](https://devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers).
* [Using Cloudflare with your API](https://support.cloudflare.com/hc/en-us/articles/200504045-Using-Cloudflare-with-your-API).

## Security

* [Helmet, help secure Express/Connect apps with various HTTP headers](https://www.npmjs.com/package/helmet).
* [APISecurityBestPractices](https://github.com/GitGuardian/APISecurityBestPractices).
* [Node Security Project](https://nodesecurity.io/).
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
* [public apis](https://github.com/toddmotto/public-apis) – A collective list of public JSON APIs for use in web development.

### Directory

* [apis.io](http://apis.io) – API Search service to help discover APIs on the web.
* [Mashape](https://market.mashape.com/explore).

## Testing

### Querying

* [Firecamp](https://firecamp.io) – Protocol agnostic API testing client which help you test and manage RestAPIs, GraphQL, Websocket and many more.
* [httpie](https://github.com/jkbrzt/httpie) – Command line HTTP client, far more dev-friendly than `curl`.
* [HttpMaster](http://www.httpmaster.net) – GUI tool for testing REST APIs and services. Windows OS only.
* [jq](https://github.com/stedolan/jq) – Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
* [Insomina](https://insomnia.rest/) – A Fancy HTTP REST Client.
* [resty](https://github.com/micha/resty) – Little command line REST client that you can use in pipelines (bash or zsh).
* [TestMace](https://testmace.com) – A modern powerful crossplatform tool for working with API and creating automated API tests.

### Mocking

* [Beeceptor](https://beeceptor.com) - Beeceptor helps intercepting API calls and mocking them selectively. Creates an endpoint for wrapping original API and routes requests.
* [FakeRest](https://github.com/marmelab/FakeRest) – Patch XMLHttpRequest to fake a REST API client-side.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) – Free online REST service that you can use whenever you need some fake data.
* [json-server](https://github.com/typicode/json-server) – Get a full fake REST API with zero coding in less than 30 seconds.
* [Mocky.io](http://www.mocky.io/) – Free online service to create fake HTTP responses.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) – Mock RESTful API based on swagger schema
* [FakeQL](https://fakeql.com/) – Mainly focused on GraphQL, but can mock RESTful APIs, as well.

### Response

* [httpstat.us](https://httpstat.us) – A super simple service for generating different HTTP codes.
* [httpbin](https://httpbin.org) – httpbin(1): HTTP Request & Response Service.
* [badssl](https://badssl.com) – Testing clients against bad SSL configs.

## Documentation

> One of the most important part of your API is have a good documentation and updated with the code.

### Free

* [docbox](https://github.com/tmcw/docbox) ([demo](https://67-53007065-gh.circle-artifacts.com/0/tmp/circle-artifacts.NCC9T6a/index.html#our-api)).
* [slate](https://github.com/tripit/slate) ([demo](https://lord.github.io/slate/#introduction)).
* [whiteboard](https://github.com/mpociot/whiteboard) ([demo](http://marcelpociot.de/whiteboard)).

### Services

* [RapidAPI](https://docs.rapidapi.com/docs).
* [Readme.io](https://readme.io/).

## Logging

* [keymetrics.io](https://keymetrics.io).
* [morgan for expressjs](https://github.com/expressjs/morgan).

## Modeling and SaaS

> Based in DDD (Domain Driven Development). Generates automatically API's in different languages.

* [Alteranatives to API Plug](https://www.producthunt.com/alternatives/api-plug) – 9 alternative and related products to api plug.
* [Apiary](https://apiary.io/) – Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [wrapAPI, Build an API on top of any website](https://wrapapi.com).
* [import.io, turn web pages into Data](https://www.import.io/).
* [RAML, RESTful API Modeling Language](http://raml.org).
* [Runscope](https://www.runscope.com/) – Automated API Monitoring & Testing.
* [swagger.io](http://swagger.io).

## Libraries

> Used it to improve your workflow

* [hello.js](http://adodson.com/hello.js/#hellojs) – A client-side Javascript SDK for authenticating with OAuth2.
* [nock](https://www.npmjs.com/package/nock) – HTTP Server mocking for Node.js
* [node-ratelimiter](https://github.com/tj/node-ratelimiter) – Rate limiter for Node.js backed by Redis.
* [node-uuid](https://github.com/broofa/node-uuid) – Simple and fast generation of UUIDS.
* [Supertest](https://www.npmjs.com/package/supertest) – Super-agent driven library for testing HTTP servers.
* [Unirest](http://unirest.io) – Lightweight HTTP Request Client Libraries.

## Frameworks

> Designed specifically for building RESTful API's Quickly.

* [Loopback](http://loopback.io).
* [Sails.js](http://sailsjs.org).
* [FastAPI](https://github.com/tiangolo/fastapi).
* [rest-hapi](https://resthapi.com).

## Gateways

> Manage API infrastructure concerns such as authentication/authorization, rate limiting, scaling, analytics, etc.

### Open Source / Self-hosted

* [API Umbrella](http://apiumbrella.io/).
* [ApiAxle](http://apiaxle.com).
* [KrakenD](http://krakend.io).
* [Mashape Kong](https://getkong.org/).
* [Tyk](https://tyk.io/).
* [WSO2 API Manager](http://wso2.com/api-management/try-it/).
