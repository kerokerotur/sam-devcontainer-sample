.PHONY: build

build:
	sam build

run:
	sam local invoke --container-host host.docker.internal --container-host-interface 0.0.0.0

run2:
	sam local invoke --container-host 172.18.0.1 --container-host-interface 172.18.0.1

# $ cd sam-app/
# $ sam local invoke --container-host host.docker.internal --container-host-interface host.docker.internal