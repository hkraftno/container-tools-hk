CONTAINER_NAME = eu.gcr.io/hkraft-ci/hk-sed
push:: build
	docker push $(CONTAINER_NAME)
build::
	docker build -t $(CONTAINER_NAME) .
