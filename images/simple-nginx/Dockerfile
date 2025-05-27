FROM nginx:stable-alpine
RUN apk update && apk upgrade && apk add curl
COPY index.html /usr/share/nginx/html/index.html
#CMD ["nginx", "-g", "daemon off;"]
ENTRYPOINT ["nginx", "-g", "daemon off;"]