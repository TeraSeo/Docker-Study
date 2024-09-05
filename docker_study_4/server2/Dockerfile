FROM nginx

COPY webapp /usr/share/nginx/html

ENTRYPOINT ["nginx", "-g", "daemon off;"]

# docker_study_4 폴더 위치에서
# docker build -t server2 ./server2
# docker run -d -p 8002:80 server2