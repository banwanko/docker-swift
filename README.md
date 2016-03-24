# docker-swift

An Ubuntu 15.10 Docker image for [Swift](https://swift.org) 2.2.

You can find the Docker Hub repo here: [https://hub.docker.com/r/roworks/swift/](https://hub.docker.com/r/roworks/swift/)

## Docker Instructions

### Pull the Docker Image From Docker Hub.

```
docker pull roworks/swift
```

### Create a container from image and attach it.

```
docker run --name swift2.2 -dit --privileged roworks/swift:latest
```

## License

docker-swift is licensed under the [MIT License.](LICENSE.md)