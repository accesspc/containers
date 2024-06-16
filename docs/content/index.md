# Docker containers

## Docker build

Docker allows to run a multi-platform build and push to docker hub. To do so, first need to start the build instance:

```bash
# Prepare build instance
docker buildx create --use
```

Run the build commands with `--platform=...` arguments.

Stop and remove build instance after builds are complete:

```bash
# Stop and remove build instances
docker buildx stop
docker buildx rm
```
