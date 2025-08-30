FROM almalinux:9   
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ADD https://github.com/vishnusai34/docker-practice/blob/112afe43a09cad9afef389ab5883ba593d2cb4bf/sample%20file/sample.tar /usr/share/nginx/html/index.html
RUN chmod -R 755 /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]