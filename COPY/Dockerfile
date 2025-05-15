FROM almalinux:9

RUN yum install nginx -y 

COPY index.html /usr/share/nginx/html 

CMD ["nginx","-g","daemon off;"]


