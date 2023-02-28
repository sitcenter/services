include .env

.PHONY: restart
restart:
	make rm up

.PHONY: rm
rm:
	docker rm -f ${CONTAINER_NAME}

.PHONY: up
up:
	docker compose up -d

.PHONY: rm_volume
rm_volume:
	rm -rf ${VOLUME_JENKINS}