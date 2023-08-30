# PostgreSQL using Docker Compose

This project let's you quickly spin up a PostgreSQL Docker container using Docker Compose from the terminal for local development and learning purposes.


## Prerequisites 
You need to have Docker Engine and Docker Compose on your machine.

You can install [Docker Desktop](https://docs.docker.com/desktop/) which includes both Docker Engine and Docker Compose

## How to run
```bash
# Clone repository
$ git clone https://github.com/Diego-Paris/Postgres-Docker

# Run docker compose
$ docker-compose up -d
# or
$ docker compose up -d
```

## How to connect
You can connect to your new database using your favorite database tool. Two great options are [pgAdmin 4](https://www.pgadmin.org/) and [DataGrip](https://www.jetbrains.com/datagrip/). You can also connect from the command line using [psql](https://www.timescale.com/blog/how-to-install-psql-on-mac-ubuntu-debian-windows/).

```yaml
# Information needed to connect to your database
# All of this can be changed inside of docker-compose.yml
Hostname/Address: localhost
Port: 5555
Username: postgres
Password: password
```

### Notes
This project is for learning and local development purposes only. This is not intended for a production environment.