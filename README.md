# WebChat - React Client Interface

This project is an interface to a web chat used to learn React and some other
languages.

The main objective of the project is to study programming languages and
techniques, it has not been improved for deployment on a production server,
only development environment.

Application developed following tutorial from https://www.youtube.com/watch?v=LvfJ2wEpMrs&list=PLMhAeHCz8S3_VYiYxpcXtMz96vePOuOX3
The full course is spreaded between some few github projects, this interface is
based on the last one, provided here https://github.com/hidjou/node-graphql-react-chat-app/tree/class-15
The original project have all (back-end and front-end) in the same project, one
of the ideas of this project, in addition to studying the languages separately,
is to make it possible for the front-end to be used to study other back-end
languages and vice versa in a simpler way.

For options of back end projects look in my profile for a project with the name
webchat that has "server" in its name, descriptive or even in their README files.

# Pre requirements:

* git 2.17.1
* npm 6.14.6

# Installation

The project has not been improved for deploying to a production server, only
development environment.

## How to run in development environment

Just run the scripts below on any terminal and then go to the http://localhost:3000
environment to view an interface.

**IMPORTANT**: For the application to be functional, it is necessary to use some
back-end interface, otherwise the client application will generate errors
for not having any interaction API.

## Build and run the environment

Afther cloning the project you first build the node_modules at your local
machine running:
```bash
cd [projeto]
npm i
```

After building you run the command below:
```bash
cd [projeto]
npm start &
```

if you use the '&' above the npm script will be thrown to background and you can
stop it using the commands below:
```bash
kill -9 $(lsof -t -i:3000)
```

## Access

To access the application, it is necessary that both the client and the server 
are running and for this it is mandatory that this project is running on the
same server as the back-end project. While both are in operation, simply point
the Web browser at the address
``http://localhost:3000/``.

# Terms of use

This repository is made available as is, without guarantees of operation or of any nature.

The distribution laws follow the same laws as the original project mentioned at the beginning of this document.
