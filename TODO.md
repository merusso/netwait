When pulling arm image, a warning is displayed:

```
$ docker pull --platform=linux/arm64 merusso/netwait:docker-multi-arch 
docker-multi-arch: Pulling from merusso/netwait
Digest: sha256:3fcd99ff3b571d0a2107711eb512806ee108b94841a60900c409a1e65d069103
Status: Image is up to date for merusso/netwait:docker-multi-arch
WARNING: image with reference merusso/netwait was found but does not match the specified platform: wanted linux/arm64, actual: linux/amd64
docker.io/merusso/netwait:docker-multi-arch
```
