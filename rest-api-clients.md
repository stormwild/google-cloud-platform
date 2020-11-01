# Rest Api Clients

## REST clients

REST clients are apps that can be used to make HTTP requests to an API. Even though they are often referred to as "REST clients," they typically can make requests to other types of HTTP APIs as well.

In this course, you will need to use a REST client to make requests to the APIs you create.

This document explains the benefits of a few REST clients. Feel free to choose the REST client that makes sense for you.

## Apigee trace tool

The Apigee trace tool can be used to make simple API GET requests from the Apigee console. The trace tool can only be used to make GET requests with a URL, and cannot be used to make any requests with headers or a payload. You will need the ability to send headers and payloads with your requests, so you will need another REST client. Any of the following four tools will work for this course.

## curl

[Curl](https://curl.haxx.se/) was first released in 1997.

Pros: Curl is a **command-line tool** that is already installed in many operating systems. If your job requires making API calls from lots of different machines, you will often find curl already installed for you. It is also fast and fully featured. If you have extensively worked with APIs in the past, you probably already know curl. It is open source.

Cons: Curl's interface is rather complex, and it can be difficult to remember all of the command line options.

## HTTPie

[HTTPie](https://httpie.org/)

## Postman

[Postman](https://getpostman.com/)

## Hopscotch

[Hoppscotch](https://hoppscotch.io/)

## References

- [REST Clients - Comparing some popular REST clients](https://storage.googleapis.com/cloud-training/developing-apis/docs/rest-clients.pdf)