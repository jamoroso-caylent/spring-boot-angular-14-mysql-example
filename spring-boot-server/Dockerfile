FROM public.ecr.aws/docker/library/openjdk:16-jdk-alpine3.13
EXPOSE 8080
ADD target/spring-boot-data-jpa-0.0.1-SNAPSHOT.jar spring-boot-data-jpa-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "spring-boot-data-jpa-0.0.1-SNAPSHOT.jar"]