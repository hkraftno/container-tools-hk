This docker container is meant to be used like this:
```bash
docker run --rm -it -v ${PWD}:/build --workdir /build eu.gcr.io/hkraft-ci/flutter-builder /bin/bash -c "flutter pub get && flutter build web"
```


An alternative to this container is to just use cirrus-ci's container:
[cirrusci/flutter](https://hub.docker.com/r/cirrusci/flutter)