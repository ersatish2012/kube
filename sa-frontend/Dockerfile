FROM nginx:latest

RUN mv /usr/share/nginx/html /usr/share/nginx/html-bk
ADD build /usr/share/nginx/html

EXPOSE 80
