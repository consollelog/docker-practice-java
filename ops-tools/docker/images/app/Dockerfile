
FROM alpine

RUN mkdir /app \
	&& apk add openjdk8 \
	&& apk add maven

WORKDIR /app

CMD ["mvn", "spring-boot:run"]

EXPOSE 8080
