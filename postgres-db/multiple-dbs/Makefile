build-image:
	docker build -t postgres-multiple-db:latest -f ./dockerfile/Dockerfile ./dockerfile

container-up:
	docker-compose -f docker-compose.yml up -d

container-down:
	docker-compose -f docker-compose.yml down

container-stop:
	docker-compose -f docker-compose.yml stop
