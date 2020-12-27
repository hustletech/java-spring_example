FROM openjdk:15.0.1-slim

LABEL maintainer="Rodrigo Dantas"
LABEL email="rodrigo.dantas@hustletech.dev"
LABEL since="2020.12.22"

# Update image and install needed packages
RUN apt-get update -y
RUN apt-get install git -y

RUN mkdir /app

CMD tail -f /dev/null

EXPOSE 8080