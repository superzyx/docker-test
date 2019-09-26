FROM nginx:1.16.1
COPY . /etc/nginx/conf.d/
RUN rm -rf /etc/nginx/conf.d/default.conf
CMD /usr/sbin/nginx -g "daemon off;"

