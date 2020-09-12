# Traccar with MariaDB

Ceate the (traccar)[https://www.traccar.org/] server with a standalone Maria DB database and Traefik reverse proxy via docker-compose file.

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
