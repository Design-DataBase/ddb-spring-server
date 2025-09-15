# 1. Base image 지정 (OpenJDK 17 기준)
FROM openjdk:17-jdk
WORKDIR /app

# 2. jar 파일을 컨테이너에 복사
COPY build/libs/*.jar designdb.jar

# 3. 실행 명령
ENTRYPOINT ["java","-jar","/app/designdb.jar"]
