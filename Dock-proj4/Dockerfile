## image to have pre configured docker and maven
## PS: this docker has no docker.sock present so connect it to the host docker.sock file.

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive


WORKDIR /app


RUN apt-get update && apt-get install -y openjdk-17-jdk maven docker.io && rm -rf /var/lib/apt/lists/*


CMD ["mvn", "-v"]
