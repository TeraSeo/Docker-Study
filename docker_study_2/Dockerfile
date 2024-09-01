FROM ubuntu

Run apt-get update
Run apt-get install -y nginx
# -y 옵션 모든 물음에 y로 자동 대답해줌

WORKDIR /var/www/html

COPY ./webapp ./
# ./webapp 폴더 안의 내용을 /var/www/html 안에 넣어준다

ENTRYPOINT ["nginx", "-g", "daemon off;"]



# docker_study_2 folder 안으로 들어간 후 입력
## docker build -t nginx-server ./  -> nginx-server image가 만들어 진다

# nginx-server image 실행
## docker run -dit -p 8080:80 nginx-server -> 8080 port에 nginx-server를 실행시킨다.