# rinha-2024q1-crebito

## Build

### Build docker image

```sh
docker build -t rinha-2024q1-crebito .
```

### Enviando imagem manualmente para o Docker Hub

```sh
# https://stackoverflow.com/questions/57108005/login-to-docker-hub-by-command-line
docker login
# or more specifically:
docker login registry-1.docker.io
```

```sh
docker build -t guilhermerodrigues680/rinha-2024q1-crebito:latest .
docker push guilhermerodrigues680/rinha-2024q1-crebito:latest
```
