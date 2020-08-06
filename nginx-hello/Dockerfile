FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/*
ADD test-demo/nginx-hello/hello.conf /etc/nginx/conf.d/
ADD test-demo/nginx-hello/index.html /usr/share/nginx/html/
