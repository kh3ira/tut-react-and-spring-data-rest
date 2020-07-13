FROM openjdk:14-jdk-alpine
COPY target/react-and-spring-data-rest-security-0.0.1-SNAPSHOT.jar /
RUN jar -xf react-and-spring-data-rest-security-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-cp", "BOOT-INF/classes:BOOT-INF/lib/*", "com.greglturnquist.payroll.ReactAndSpringDataRestApplication"]
EXPOSE 8080