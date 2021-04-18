# docker-firebase

## enviroment

### setup

```bash
$ docker-compose build
$ docker-compose up -d
# status check
$ docker ps -a
```

```bash
# docker-compose exec <container_name>

# package install
$ docker-compose exec firebase bash -c "npm i && cd functions && npm i"

# authentication
$ docker-compose exec firebase firebase login --no-localhost

# start
$ docker-compose exec firebase bash -c "cd functions && npm run serve"
```
