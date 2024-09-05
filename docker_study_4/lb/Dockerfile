FROM nginx

COPY conf/nginx.conf /etc/nginx/conf.d/default.conf

ENTRYPOINT ["nginx", "-g", "daemon off;"]

# docker_study_4 폴더 위치에서
# docker build -t lb ./lb
# docker run -d -p 8000:80 lb