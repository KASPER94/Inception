FROM nginx:latest

COPY default.conf /etc/nginx/conf.d/default.conf
COPY fastcgi_params /etc/nginx/fastcgi_params

CMD ["nginx", "-g", "daemon off;"]
