# NextCloud Installation

Runs Docker containers for NextCloud and Postgres.

## Prerequisites

- Git

## Run with Docker Compose

1. Download the repository

   ```sh
    git clone https://github.com/devopsleigh/nextcloud.git
    cd nextcloud
    nano .env
    ```

2. Change secrets appropriately

   ```sh
   TZ=Country/City
   POSTGRES_USER=nextcloud
   POSTGRES_PASSWORD=somethingsecure
   ```

3. Run the containers

   ```sh
   sudo docker-compose up -d --force-recreate
   ```
