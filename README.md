# docker-images

Various docker images for different purposes.

## Dockerhub

Pushed to Dockerhub `ttamg76` - https://hub.docker.com/search?q=ttamg76

## Example Local build

To build the image locally

```bash
docker build -t ttamg76/langfuse:latest .
```

## Example local build multiple architectures

To build the image for multiple architectures and push

```bash
docker buildx build --platform linux/amd64,linux/arm64 -t ttamg76/langfuse:latest --push .
```
