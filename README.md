# Awesome API [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for design and implement RESTful APIs.

## Design

### Overview

> REST allows us to create services and applications that can be used by any device or client who understands HTTP.

* [HTTP API Design Guide by interagent](https://github.com/interagent/http-api-design).
*  [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api) / [Spanish version](http://elbauldelprogramador.com/buenas-practicas-para-el-diseno-de-una-api-restful-pragmatica/).
* [Ideal REST API Design] (https://betimdrenica.wordpress.com/2015/03/09/ideal-rest-api-design/).
* [Heroku API Reference](https://devcenter.heroku.com/articles/platform-api-reference).
* [API Terms Glossary](https://github.com/Mashape/apiglossary).
* [Learn REST: A RESTful Tutorial](http://www.restapitutorial.com).

### Status Code

> When you are using a REST design you have to provide the HTTP status code that are the more appropriated to respond to the request.

* [httpstatus.es](http://httpstatus.es/)
* [Status code definition in W3C](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html).
* [HTTP Status code table in RESTAPITutorial](http://www.restapitutorial.com/httpstatuscodes.html).

### Authentication

* [Authentication Cheat Sheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet).

#### JWT

> JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.

* [JWT Draft in IETF](http://tools.ietf.org/html/draft-ietf-oauth-json-web-token).
* [JWT.io](http://jwt.io/).
* [Cookies vs Tokens](https://auth0.com/blog/2014/01/07/angularjs-authentication-with-cookies-vs-token).
* [Why Meteor doesn't use session cookies](https://www.meteor.com/blog/2014/03/14/session-cookies).
* [10 Things You Should Know about Tokens](https://auth0.com/blog/2014/01/27/ten-things-you-should-know-about-tokens-and-cookies).
* [Using JSON Web Tokens as API Keys](https://auth0.com/blog/2014/12/02/using-json-web-tokens-as-api-keys).

### Authorization

#### OAuth

> An open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications

* [The OAuth Bible by Mashape](http://oauthbible.com/).

## Format

* [JSON API](http://jsonapi.org/) - Standard for building APIs in JSON.
* [RAML](http://raml.org/) - Simple and succinct way to describe RESTful API.
* [JSend](http://labs.omniti.com/labs/jsend) - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
* [OData](http://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [HAL](http://stateless.co/hal_specification.html) - Simple format that gives a consistent and easy way to hyperlink between resources in your API (see: [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
* [Hydra](http://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
* [Schema.org](http://schema.org) - Collection of schemas describing common data models.

## Discover

> Need a API for your project? Check in this sites.

* [Mashape](https://www.mashape.com/explore).
* [publicapis.com](http://www.publicapis.com).
* [apis.io](http://apis.io).

## Testing

### Querying

* [httpie](https://github.com/jakubroztocil/httpie) - Command line HTTP client, far more dev-friendly than `curl`.
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - Chrome extension essential to test manually REST API.
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines (bash or zsh).
* [jq](https://github.com/stedolan/jq) - Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
* [HttpMaster](http://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.

### Mocking

* [FakeRest](https://github.com/marmelab/FakeRest) - Patch XMLHttpRequest to fake a REST API client-side.
* [json-server](https://github.com/typicode/json-server) - Serve a REST API from fixture files using quick prototyping.
* [Mocky.io](http://www.mocky.io/) - Free online service to create fake HTTP responses.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - Mock RESTful API based on swagger schema

### Public REST APIs To Use In Tests

* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - The world's largest API repository.
* [Public APIS](https://www.publicapis.com/) - Explore The Largest API Directory In The Galaxy.
* [Marvel Comics API](http://developer.marvel.com/) - Query characters, stories, events about Marvel superheroes.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - Free online REST service that you can use whenever you need some fake data.


## Documentation

> One of the most important part of your API is have a good documentation and updated with the code.

### Free

* [apiDoc](http://apidocjs.com).
* [aglio](https://github.com/danielgtaylor/aglio).
* [slate](https://github.com/tripit/slate).

### Services

* [Readme.io](https://readme.io/).
* [Mashape](http://docs.mashape.com/documenting-api).

## Logging

* [keymetrics.io](https://keymetrics.io).
* [morgan for expressjs](https://github.com/expressjs/morgan).

## Modeling and SaaS

> Based in DDD (Domain Driven Development). Generates automatically API's in different languages.

* [RAML, RESTful API Modeling Language](http://raml.org).
* [kimono, generate API from websites](https://www.kimonolabs.com).
* [import.io, turn web pages into Data](https://import.io).
* [swagger.io](http://swagger.io).
* [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
* [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.

## Libraries

> Used it for improve your workflow

* [Unirest, Lightweight HTTP Request Client Libraries](http://unirest.io).
* [nock, HTTP Server mocking for Node.js](https://www.npmjs.com/package/nock).
* [Supertest, Super-agent driven library for testing HTTP servers](https://www.npmjs.com/package/supertest).
* [hello.js, A client-side Javascript SDK for authenticating with OAuth2](http://adodson.com/hello.js/#hellojs).


## Frameworks

> Designed specify for build quickly RESTful API's.

* [Sails.js](http://sailsjs.org).
* [Loopback	](http://loopback.io).


## Gateways

> Manage API infrastructure concerns such as authentication/authorization, rate limiting, scaling, analytics, etc.

### Open Source / Self-hosted

* [Mashape Kong](http://getkong.org/).
* [Tyk](https://tyk.io/).
* [API Umbrella](http://apiumbrella.io/).
* [ApiAxle](http://apiaxle.com).
* [WSO2 API Manager](http://wso2.com/api-management/try-it/).

