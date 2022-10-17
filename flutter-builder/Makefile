CONTAINER_NAME = eu.gcr.io/hkraft-ci/flutter-builder
push:: build
	docker push $(CONTAINER_NAME)
build::
	docker build -t $(CONTAINER_NAME) .
