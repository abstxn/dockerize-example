# Dockerized Repository Example

## Breakdown

Generally, the project repository would consist of:

- `Dockerfile`(s) throughout the project.
- A single `docker-compose.yaml` file.

The common use case for the `docker-compose.yaml` file is to orchestrate the containers that the project requires.

For example, a simple project might have 3 separate containers:

1. Client frontend
2. Backend server process
3. Backend database instance

The `docker-compose.yaml` file, used by the `docker compose` command, defines how the containers should be set up, and how they can communicate with one another.
