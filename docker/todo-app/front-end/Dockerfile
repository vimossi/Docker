FROM node:14-alpine3.13 AS todofrontend
WORKDIR /front-end
EXPOSE 3000
COPY [ ".", "./" ]
ADD node_modules.tar.gz .
RUN ["touch", ".dockerignore"]
ENTRYPOINT [ "npm", "start" ]