# Orders & Users Microservices with PostgreSQL, Kafka, and Zookeeper

This repository contains a Docker Compose setup for two microservices: `orders` and `users`, along with PostgreSQL, Kafka, and Zookeeper.

## Prerequisites
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Users](https://github.com/ac1dr3d/taks-users) & [Orders](https://github.com/ac1dr3d/taks-orders) projects in same directory using users/orders folder names.

## Services Overview
- **Orders Service**: Runs on `http://localhost:8081`
- **Users Service**: Runs on `http://localhost:8082`
- **PostgreSQL**: Available on `localhost:5432` (user: `postgres`, password: `asdASD123`)
- **Kafka**: Available on `localhost:9092`
- **Zookeeper**: Available on `localhost:2181`

## How to Run
Run the following command to start all services:
```bash
docker compose up
