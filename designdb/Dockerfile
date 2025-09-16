FROM openjdk:17-jdk
WORKDIR /app

# 실행용 부트 JAR 하나만 app.jar로 복사
COPY build/libs/*-SNAPSHOT.jar app.jar

ENTRYPOINT ["java","-jar","/app/app.jar"]
