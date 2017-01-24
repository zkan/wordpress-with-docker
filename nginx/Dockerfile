FROM nginx:1.11.8-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY wordpress.conf /etc/nginx/conf.d/wordpress.conf

CMD /usr/sbin/nginx -g "daemon off;"
