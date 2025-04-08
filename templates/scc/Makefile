docker_build:
	docker build -t sapcc .

docker_deploy:
	docker tag sapcc ghcr.io/b-tocs/btocs_sapcc:v$(VERSION)
	docker push ghcr.io/b-tocs/btocs_sapcc:v$(VERSION)

docker_deploy_latest:
	docker tag sapcc ghcr.io/b-tocs/btocs_sapcc:latest
	docker push ghcr.io/b-tocs/btocs_sapcc:latest