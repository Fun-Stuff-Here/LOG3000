FROM nginx

RUN apt-get update && apt-get install -y git

RUN git clone https://github.com/varunks99/LOG3000-Docker-TP.git /app

RUN cp -r /app/* /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
