FROM nginx

ADD nginx.conf /etc/nginx/nginx.conf
ADD nginx.default /etc/nginx/conf.d/default.conf
ADD theme /app/gamedvr/.theme

EXPOSE 80

ENTRYPOINT nginx


