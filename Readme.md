## 📌 도커 이미지
### 1. 도커 이미지 빌드
```$ docker build -t issuemoa/eureka .```
- -t 빌드할 이미지의 이름 
- . (현재 위치 기준에서 Dockerfile을 찾는다.)

### 2. 도커 이미지 확인
```$ docker image ls```
```
REPOSITORY      IMAGE ID        CREATED        SIZE     TAG          
issuemoa/eureka 954d2adb5a88    1 hours ago    510MB    latest
```

### 3. 도커 컨테이너 실행
```$ docker run -d --name=issuemoa-eureka -p8761:8761 issuemoa/eureka```
- -d 백그라운드로 실행
- --name 컨테이너명 설정
- -p 포트 설정
- 이미지명

---

## 📌 도커 컴포즈
### 도커 컴포즈 실행
```docker-compose up```

### 실행중 컨테이너 확인
```docker ps```
