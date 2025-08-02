# n8n Local Setup with [Docker, PostGres and Worker](https://github.com/n8n-io/n8n-hosting/tree/main/docker-compose/withPostgresAndWorker)

To start n8n simply start docker-compose by executing the following command in the current folder.

> IMPORTANT: But before you do that change the default users and passwords in the .env file!

```bash
docker-compose up -d
```
To stop it execute:

```bash
docker-compose stop
```

#### Configuration
The default name of the database, user and password for PostgreSQL can be changed in the .env file in the current directory.

