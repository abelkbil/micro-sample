FROM ngnix
RUN rm -rf /usr/share/nginx/html/*
COPY Docker.nginx.default.conf /ect/nginx/conf.d/
COPY dist /usr/share/nginx/html
EXPOSE 80
EXPOSE 443
