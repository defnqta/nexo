1. The Dockerfile was build locally with

```
docker build -t nexo:latest
```

2. Docker-compose was also build locally using

```
docker stack deploy -c docker-compose.yaml nexo
```

3. Using Github Actions the image was built and pushed to a Docker Hub registry. 

4. No local Minikube environment, deployed everything using Github Actions.
