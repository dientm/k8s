FROM nginx:1.15

WORKDIR /app

COPY dist/Angular6SpringBoot/ /usr/share/nginx/html

COPY nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
