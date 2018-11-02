FROM python:3.6.7-alpine3.6

MAINTAINER Robert Metcalf

COPY ./main_entrypoint.sh /main_entrypoint.sh
COPY ./app /app

RUN chmod +x ./main_entrypoint.sh


ENTRYPOINT ["./main_entrypoint.sh"]

##DOCKER_USERNAME=metcarob
##DOCKER_IMAGENAME=pythonpoc_001
##docker build . -t ${DOCKER_USERNAME}/${DOCKER_IMAGENAME}:latest
##docker run -it --name xxx -p 80:80 -d ${DOCKER_USERNAME}/${DOCKER_IMAGENAME}:latest python --version
##docker run -it --name xxx -p 80:80 -d ${DOCKER_USERNAME}/${DOCKER_IMAGENAME}:latest /bin/sh

##docker run --name xxx --entrypoint /bin/sh -it ${DOCKER_USERNAME}/${DOCKER_IMAGENAME}:latest

#COnnect to running container
##docker exec -it xxx /bin/sh

#Run an app inside an image (container not running)
##docker run --name xxx -it ${DOCKER_USERNAME}/${DOCKER_IMAGENAME}:latest


