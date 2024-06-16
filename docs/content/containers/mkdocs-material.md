# mkdocs-material

Docker image based on [squidfunk/mkdocs-material](https://hub.docker.com/r/squidfunk/mkdocs-material), but run as user id 1000 to avoid ssh permissions issues during pages push to Github.

## Build and push to Docker Hub

```bash
docker buildx build --platform=linux/amd64,linux/arm64 --push -t accesspc/mkdocs-material:9.5.26 .
docker buildx build --platform=linux/amd64,linux/arm64 --push -t accesspc/mkdocs-material:9.5 .
docker buildx build --platform=linux/amd64,linux/arm64 --push -t accesspc/mkdocs-material:9 .
docker buildx build --platform=linux/amd64,linux/arm64 --push -t accesspc/mkdocs-material:latest .
```
