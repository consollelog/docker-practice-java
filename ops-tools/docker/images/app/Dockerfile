#FROM maven:3.3-jdk-8-alpine

#RUN mkdir /app 
#	&& apk add openjdk8 \
#	&& apk add openjdk8-jre \
#	&& apk add maven

#WORKDIR /app

#CMD ["mvn", "spring-boot:run"]

#EXPOSE 8888

FROM debian

RUN mkdir /app \
	&& apt-get update \
	&& apt-get install default-jre -y \
	&& apt-get install default-jdk -y \
	&& apt-get install maven -y

WORKDIR /app

CMD ["mvn", "spring-boot:run"]

EXPOSE 8080
