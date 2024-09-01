FROM openjdk:11-jdk-slim

WORKDIR /app

COPY build/aws-v3-0.0.3.jar ./application.jar

ENTRYPOINT ["java", "-jar", "-Dspring.profiles.active=dev", "application.jar"]

CMD ["--server.port=3000"]

# ENTRYPOINT안의 내용은 터미널에서 입력시에 변경이 불가능 하지만 CMD의 명령은 터미널에서 명령어를 통해 덮어쓸 수 있다.

# docker_study_1 folder 안으로 들어간 후 입력
## docker build -t java-server ./  -> java-server image가 만들어 진다

# java-server image 실행
## docker run -dit -p 8080:80 java-server -> 8080 port에 java-server를 실행시킨다.