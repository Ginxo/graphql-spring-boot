FROM java:8
MAINTAINER Enrique Mingorance Cano "ginxaco@gmail.com"
VOLUME /tmp
ADD poc-grapql-api-gen-0.1.0-fat.jar graphql-micro.jar
RUN bash -c 'touch /graphql-micro.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/graphql-micro.jar"]