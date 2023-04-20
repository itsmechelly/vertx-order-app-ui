# vertx-order-app-ui
This repo contain the ui web page I created for the vertex-order-app, it's only a preview for the project.<br/>
To view the preview page [please CLICK HERE](http://vertx-order-application.s3-website-eu-west-1.amazonaws.com/).<br/>
For the vertx-order-app source code [please CLICK HERE](https://github.com/itsmechelly/vertx-order-app).<br/>

![vertx-order-app drawio](https://user-images.githubusercontent.com/60425986/229585752-c683974f-0c4e-4f0f-b805-5d4c1ecefe92.png)

### 🤔 What is the purpose of this application?
This Project represents a small Microservice App using Eclipse Vert.x and Hazelcast In-Memory Data Grid.
### 💬 What is Eclipse Vert.x?
Eclipse Vert.x is a tool-kit for building reactive asynchronous applications on the JVM.
Reactive applications are both scalable as workloads grow, and resilient when failures arise.
### 💬 How it works?
The project is a Maven project, written by Java language and includes 2 modules that will be communicate with Vert.x Event Bus, the two modules are:
 - RestVerticle module
 - OrderVerticle module

# Extra Details

### 👉 Communication Between the Microservice Modules
The communication between the two verticles will be by using [Vert.x Event Bus](https://vertx.io/).
### 👉 Cluster Manager
The Application will be running in cluster mode by using [Hazelcast In-Memory Data Grid (IMDG)Open Source](https://hazelcast.com/).
### 👉 Docker
The maven package will be generating a docker-compose YAML that will contain two containers for the 2 verticles.

# 🛠 Tech Stack
Language & Framework: Java, Maven
<br/>
Asynchronous Tools: Eclipse Vert.x
<br/>
In-Memory Data Grid (IMDG): Hazelcast
<br/>
Architecture & Design Patterns: Microservice Application, Reactive Application
<br/>
Client-Side UI: HTML, CSS, Bootstrap 5
<br/><br/>
