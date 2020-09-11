FROM nginx

RUN rm -f /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/
COPY tomcat.conf /etc/nginx/conf.d/
COPY nginx-selfsigned-cert.* /etc/nginx/certs/
