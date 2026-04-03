FROM nginx:alpine
RUN apk add --no-cache curl
COPY Devops_Intern.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
