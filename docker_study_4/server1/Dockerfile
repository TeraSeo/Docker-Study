FROM nginx

COPY webapp /usr/share/nginx/html

ENTRYPOINT ["nginx", "-g", "daemon off;"]

# docker_study_4 폴더 위치에서
# docker build -t server1 ./server1
# docker run -d -p 8001:80 server1