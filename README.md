# API Gateway Demo
## Introduction

What you will learn:

* What is an API gateway. Why is it required and what are its tasks.
* Connect the frontend of a simple ToDo app with a backend by exposing the API using Gravitee, an open-source API management platform that provides tools to secure, publish, manage, and monitor APIs.
* What are plans and flows (aka policies) and how to add them to the API gateway using yaml files or through the Gravitee UI.
* Future: Adding AM (Access Management) to the API gateway.

What you need:

* Docker
* Postman Desktop App (API development and testing tool, allows us to easily make requests to the gateway and see the corresponding responses.)

If you are completely new to certain basic topics, I recommend taking a look at: [Basics](https://community.gravitee.io/t/part-1-the-essentials/1458)
It includes small introductions to APIs in general, the network stack and its protocols, specifications such as OpenAPI, etc.

You can find a more in-depth introduction into API gateways here: https://community.gravitee.io/t/part-2-gravitee-key-concepts-and-core-offerings/1459
This introduction uses Gravitee as an example, but many of the key concepts apply generally regardless of the used API management tool. I recommend having a lookt at:
* [Overview](https://community.gravitee.io/t/part-2-gravitee-key-concepts-and-core-offerings/1459)
* [API Gateway: Policies and Plugins](https://community.gravitee.io/t/part-2-gravitee-key-concepts-and-core-offerings/1459#api-gateway-policies-and-plugins-5)

## DEMO
The following tutorial is based on: [Gravitee Demo](https://community.gravitee.io/t/part-3-getting-started/1460). You can also follow the steps there. However, the tutorial uses Thunder Client which requires a license in order to follow the steps. We use Postman instead.

First you need to run the containerized application:
```
docker compose up -d
```
The Docker Desktop app will now show you all of the services running in the container.
![View in Docker Desktop](./images/docker.png)