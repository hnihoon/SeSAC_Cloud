# 베이스이미지 지정
FROM node:lts
# /app 폴더에서 cmd 명령어가 진행됨 
# ※폴더가 없으면 생성해줌
WORKDIR /app
# 현재 폴더에 복사함
# ※WORKDIR 이 있으므로 /app에 복사됨
COPY ./package.json ./
RUN npm install

#[호스트] 파일 또는 폴더를 [컨테이너]로 복사
#[호스트 파일] [컨테이너 경로로]
# COPY ./app.js /app.js 
# CMD ["node", "app.js"]

# docker build -t my-node . : 파일을 복사해서 생성
# docker run --name my-node-container -itd my-node : 이름을 지정해서 생성과 동시에 실행
# docker run my-node : 이름 지정없이 실행
# docker exec -it my-node-container bash : 접근
# ls : 조회

#docker rm -f my-node-container : 삭제