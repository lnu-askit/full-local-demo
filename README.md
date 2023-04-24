# Askit Local Demo

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Git](https://git-scm.com/)
- A terminal with access to docker (Not CMD on Windows)

## Setup

1. Clone this repository with this command `git clone --recurse-submodules https://github.com/lnu-askit/full-local-demo.git`
2. Copy example.env to .env and fill in the values
3. Run `docker compose up`
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Tear down

1. Run `docker compose down --rmi all --volumes`
