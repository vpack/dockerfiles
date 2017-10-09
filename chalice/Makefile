
TAG = vpack/chalice:1.0.3

chalice: DOCKERFILE = Dockerfile.chalice
chalice: TAG = vpack/chalice:1.0.3
chalice: 
	docker build -f ${DOCKERFILE} -t ${TAG} .

clean:
	docker rmi ${TAG}

test:
	docker run -it --rm ${TAG}
