## docker of storydiffusion-dev

### build docker
```shell
docker build . -t samge/storydiffusion-dev-base -f .devcontainer/Dockerfile-dev-base --build-arg PROXY=http://192.168.50.48:7890
```

### upload
```shell
docker push samge/storydiffusion-dev-base
```

### run .devcontainer/devcontainer.json