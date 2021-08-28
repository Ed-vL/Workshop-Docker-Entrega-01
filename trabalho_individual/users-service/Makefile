.PHONY: build

build:
	docker build -t users-service .

.PHONY: run

run:
	docker run --rm -p 7101:7101 -it users-service