# asciibinder Image

## Build with Podman

```sh
podman build -t apimastery/asciibinder:ruby26 -f ./Containerfile
```

Then tag it for the destination image repository and push it. For example:
```sh
podman tag localhost/apimastery/asciibinder:ruby26 docker.io/apimastery/asciibinder:ruby26
podman rmi localhost/apimastery/asciibinder:ruby26
podman push docker.io/apimastery/asciibinder:ruby26
```
