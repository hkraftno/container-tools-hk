This docker container is meant to be used like this:
```bash
docker run --rm -it -v ${PWD}:/build --workdir /build eu.gcr.io/hkraft-ci/flutter-builder /bin/bash -c "flutter pub get && flutter build web"
```
