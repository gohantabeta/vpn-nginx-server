FROM nginx:latest

ADD ./conf/default.conf /etc/nginx/conf.d/default.conf
ADD ./src /usr/share/nginx/html

EXPOSE 8080

RUN service nginx start