TAG=ctfd-kookie
all:
	docker build -t $(TAG) .

run:
	docker run --rm -p 4455:4455 -ti $(TAG)

push:
	docker push $(TAG)

clean:
	docker rm $(TAG)
