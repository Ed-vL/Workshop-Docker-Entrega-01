.PHONY: build

build:
	docker build -t chat-service .

.PHONY: run

run:
	docker run --rm -p 7100:7100 -it chat-service