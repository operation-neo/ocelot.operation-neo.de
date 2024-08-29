# ocelot.operation-neo.de

```bash
# start the containers
$ sudo docker compose -f docker-compose.ocelot-operation-neo.yml up -d
# check for local listening ports
$ sudo netstat -tulpn | grep LISTEN
```

On neo server we actually using release `b3.2.0-748` with modified Docker Compose YAML `docker-compose.ocelot-operation-neo.yml` copied from here into folder `deployment` and started as branded configuration with `docker compose up` in that folderoce.

