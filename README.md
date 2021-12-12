# Node Dockerizing Tutorial

### 프로젝트 진행 이유

도커를 활용한 CI/CD 구성을 위한 튜토리얼

### Version

node.js : v14.17.1
docker node.js : node:12

### 프로젝트 단계

step1. Node.js 공식문서를 참고하여 튜토리얼 생성

### 비고

docker build . -t kdh/node-web-app   
docker run -p 49160:8080 -d kdh/node-web-app   

### 참고

https://nodejs.org/ko/docs/guides/nodejs-docker-webapp/
