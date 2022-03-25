# Crud Management

## Installation

After clone this repository you need execute this command to clone the git submodules of FrontEnd and Backend repositories.

Use this command to clone the modules

```docker
git submodule update --init --recursive
```

## Usage

This project use Docker to setup the production stage and mongo db images to persist data

To deploy the environment use docker-compose with the command below:

```docker
docker-compose up --build
```

## License
[MIT](https://choosealicense.com/licenses/mit/)