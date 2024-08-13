# langfuse-docker

Langfuse backend and client Docker image

## Local build

To build the image locally

```bash
docker build -t ttamg76/langfuse:latest .
```

To build the image for multiple architectures and push

```bash
docker buildx build --platform linux/amd64,linux/arm64 -t ttamg76/langfuse:latest --push .
```

## Dockerhub

This image is available on Dockerhub - https://hub.docker.com/repository/docker/ttamg76/langfuse/general
