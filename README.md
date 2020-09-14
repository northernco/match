# Northern Match

A CSS reset by [Northern Commerce](https://www.northern.co/).

## Getting Started

Match can be added to a project by running the following:

```bash
yarn add @northern/match
```

## Contributing

### Requirements

  * [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
  * [Docker Compose](https://docs.docker.com/compose/install/)

### Setup

```bash
$ git clone https://github.com/northernco/match.git
$ cp docker-compose.dev.yml docker-compose.override.yml # Update override file as needed
$ docker-compose run node yarn install
```

View the demo page by opening `index.html`.

### Compiling

New assets can be compiled by running:

```bash
$ docker-compose run node yarn build
```

### Linting

Assets can be linted by running:

```bash
$ docker-compose run node yarn lint
```
