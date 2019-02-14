# Docker Images to Build Loud ML with CircleCI

Requirements:
- Docker
- DockerHub credentials

## Instructions

Log into DockerHub:

```
docker login -u $DOCKER_USER -p $DOCKER_PASS
```

Build image:

```
docker build -t $DOCKER_USER/circleci-loudml .
```

Deploy image:

```
docker push $DOCKER_USER/circleci-loudml
```
