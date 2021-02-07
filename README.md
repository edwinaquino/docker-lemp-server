# Simple LEMP Docker Container

> This app contains all the necessary configuration files to build a Docker container that runs with Nginx, MySQL and PHP. Follow the instructions below on how to get it running in your local environment. A LEMP environment is often used for backend stack. This app was developed in a Linux Ubuntu 20TLS environment but will also work on a Windows or MacOS development environment - That's the beauty of Docker.

## App Info
This is a very light-weight app which contains the necessary files to install and run a LEMP stack server in a Docker container. Very simple and straight forward.

## Requirements
* Docker
* Git
* Terminal

## Getting Started
To get started follow these steps below. In this example, we are going to create a PHP app called "docker-lemp-server" with a simple hello world.

1. Clone this repository<br>
```$ git clone https://github.com/edwinaquino/docker-lemp-server.git```
2. Change directory into the app.<br>
```$ cd docker-lemp-server```<br>
3. Build the docker container in your local machine. <br>
```$ docker-compose up -d --build```

If this is the first time building this container, this make take a while to build the container. Approximately 5 minutes depending on your environment and network connection.

after the build has completed, you will notice a new directory called "app" is created. Let’s create a public directory and an index file to make sure our app is serving PHP files;

4. open: http://localhost:8080/

You will see the index.php file with output text: Hello World

The index.php file is found in the app/public folder of this app.

Hope that works for you.

### Author

Edwin Aquino

### Version

1.0

### License

This project is licensed under the Apache License 2.0
