# mini-static-server

simple nginx docker container to easily serve static files.


## Examples

```shell
# run from docker registry
docker run mutterio/mini-static-server \
  -p 8085:80 \
  -v ./public:/var/www/files
```

```shell
# start with defaults from repo
docker-compose up

# this will create a 'public' folder in root of repo and
# serve files on port 8050
```
