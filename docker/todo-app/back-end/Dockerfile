FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . .
CMD [ "npm", "start" ]

# FROM nginx
# COPY ./index.html /usr/share/nginx/html
# EXPOSE 3000
# ENV API_URL=http://localhost:8000/api/
# WORKDIR /the/workdir/path
# RUN ls
# ENTRYPOINT [ "/usr/sbin/nginx" ]
# CMD [ "-g", "daemon off;" ]