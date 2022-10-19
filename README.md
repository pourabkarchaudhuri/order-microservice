# Order Microservice

This repository consists of Order service it is one of the services in the microservice architecture.

## Download and Installation

To begin using this framework, choose one of the following options to get started:
* Clone the repo: `git clone [https://github.com/pourabkarchaudhuri/order-microservice.git)`
* [Fork, Clone, or Download on GitHub](https://github.com/pourabkarchaudhuri/order-microservice.git)

### Technology

This service uses a number of open source packages to work properly. The following tools were used:

* [node.js] - for the backend
* [Express] - fast node.js network app framework


### Customer

It is a Node.js module that contains different endpoints to manage orders of the customers. We can perform various CRUD operations related to orders.

### Installation

Express requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies and start the server.

```sh
$ npm install
$ npm start
```

### Build a docker image

To build a docker image navigate to the location of the Dockerfile which is the root folder here and run

```sh
$ docker build -t [docker_image] .
```

### Run a container using the docker image

To spin up a container run

```sh
$ docker container run --name [container_name] [docker_image]
```

### Run on Kubernetes

To run it as a pod in the kubernetes cluster navigate to the directory where the yml configurations of the deployments and service are present and run

```sh
$ kubectl apply [file_name].yaml
```


