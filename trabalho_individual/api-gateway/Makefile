.PHONY: build

build:
	docker build -t api-gateway .

.PHONY: run

run:
	docker run --rm -p 7000:7000 -it api-gateway