# Docker Demo Project Readme

Welcome to the Docker Demo Project repository! This project serves as a basic demonstration of Docker containerization using a Node.js application. It was created as part of the learning journey with Techworld with Nana on YouTube.

## Table of Contents

- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Contributing](#contributing)


## Project Overview

This project illustrates the process of containerizing a Node.js application using Docker. The application is a simple web server built with Express that responds with a welcome message when accessed.

The repository contains the following files:
- `Dockerfile`: Instructions for building the Docker image
- `package.json`: Node.js package configuration
- `server.js`: Simple Express web server code

## Prerequisites

Before you begin, ensure you have the following prerequisites:
- Docker installed on your machine

## Usage

To build and run the Docker container with the Node.js application, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/Unnatimishra-14/Docker-demo-project.git
   cd Docker-demo-project
   ```

2. Build the Docker image:

   ```
   docker build -t Docker-demo-app .
   ```

3. Run the Docker container:

   ```
   docker run -p 3000:3000 Docker-demo-app
   ```

4. Access the application in your web browser at `http://localhost:3000`.

## Contributing

Contributions are not expected for this demo project. However, if you have suggestions or improvements, feel free to create an issue or fork the repository.




