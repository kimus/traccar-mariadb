# Traccar with MariaDB

Ceate the [Traccar](https://www.traccar.org/) GPS tracking server with a standalone Maria DB database and Traefik reverse proxy via docker-compose file.



## Instructions

Start up Traccar (`traccar`) and Maria DB (`traccar_db`) containers:

```bash
docker-compose up -d
```


Check the logs:
```bash
docker-compose logs -f
```

or you can just check the logs of `traccar` container:

```bash
docker-compose logs -f traccar
```


Restart:

```bash
docker-compose restart traccar
```

Shutdown:

```bash
docker-compose restart traccar
```
