FROM azul/zulu-openjdk-alpine:11
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
MAINTAINER Ramazan Sakin <ramazansakin63@gmail.com>
ADD target/account-service.jar account-service.jar
EXPOSE 2222
ENTRYPOINT ["java", "-jar", "/account-service.jar"]