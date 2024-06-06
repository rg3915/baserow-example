# baserow-example

Example of Baserow with Docker-compose.

Run

```bash
docker-compose up --build -d
```

Access http://localhost:8004

and doc on http://localhost:8004/api-docs


## Baserow

**Documentation:** https://baserow.io/docs/

![](img/01.png)

![](img/02.png)

![](img/03.png)



## PGAdmin

To connect on PostgreSQL with PGAdmin this connection is

![](img/pgadmin.png)


## logs

To view logs of container type

```bash
docker container logs -f baserow
```