# Python Data Science Notebook
This repo has all the requirements fulfilled for the python data science lab assignment

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KarteekaU/My-Datascience-Notebook/HEAD)

The built image is [hosted on Docker-Hub](https://hub.docker.com/layers/kaup1074/my-datascience-notebook/latest/images/sha256-48f8e3077ff6573b3e4bd42849da4a70bbe8cae555536febb10f80c2932ad486?context=repo).

## Using this repo
### With `docker`
Build:

```bash
docker build --rm -t kaup1074/my-datascience-notebook
# Built an image on dockerhub in the my data science notebook repo
```

Run:

```bash
docker run --rm -it -p 8888:8888 -v "/Users/kay4/Documents/GitHub/My-Datascience-Notebook:/home/jovyan/work" kaup1074/my-datascience-notebook
# Publishes port 8888
# Mounts the local directory as a volume in the container's home directory
```

### With `docker-compose`
Build and run:

```bash
docker-compose up
# - This command publishes port 8888 and mounts the local directory as a volume in the container's home directory
# pushes to my Dockerhub repository
```
