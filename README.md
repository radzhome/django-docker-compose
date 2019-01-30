# Django project examplifying docker-compose 

* See https://docs.docker.com/compose/django/

## Start all services

```bash
docker-compose up
```

## Make sure all is shut down
```bash
docker-compose down
```

### Start web server only

```bash
sudo docker-compose run web
```

## Docker double up (w/ scale)

```bash
# Remove exposing of port for db first, then
docker-compose up --scale db=2
```
