FROM nginx:1.16.1
COPY ./server.conf /etc/nginx/conf.d/server.conf
COPY ./login.html /usr/share/nginx/html/index.html
COPY . /usr/share/nginx/html/
CMD /usr/sbin/nginx -g "daemon off;"

