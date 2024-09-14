# How build docker image using the dockerfiles from this repo

## Qualys Client

- Run the following command to build the image of Qualys Client

```
docker build -t <your tag name> .
```

## Redis Client

- Run the following command to build the image of Redis Client

```
docker build -t <your tag name> -f Dockerfile-redis .
```

## Jira Client

- Run the following command to build the image of Jira Client

```
docker build -t <your tag name> -f Dockerfile-jira .
```

## How to pull the images from my dockerhub?

- To pull the three images run the following commands in Linux or docker desktop with WSL enabled

```
docker pull hardikrathod/qualys-client:latest
docker pull hardikrathod/redis-client:latest
docker pull hardikrathod/jira-client:latest
```