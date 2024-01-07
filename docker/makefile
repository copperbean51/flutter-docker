# makefile

dockerimage-build: 
	docker-compose build

dockercontainer-build:
	docker-compose up -d

into-container:
	docker exec -it flutter bash

webserver-start:
	flutter run -d web-server --web-port=${WEB_SERVER_PORT} --web-hostname 0.0.0.0