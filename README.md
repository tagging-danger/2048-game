# 2048-game
But it works on my machine 🤭
# Dockerized 2048 Game

This repository contains files to create a Docker image that runs the popular 2048 game served by an nginx web server.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

You need to have Docker installed on your machine to run this project.

- [Docker](https://docs.docker.com/get-docker/)

### Building the Docker Image

Run the following command to build the Docker image:
docker build -t mynginx .


### Running the Docker Container

Once the image is built, run the Docker container with:

docker run -d -p 80:80 mynginx


You can now access the 2048 game by opening a web browser and navigating to http://localhost.

## Authors

- [Your Name](https://github.com/tagging-danger/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
