FROM node:14-alpine3.13 AS todobackend
WORKDIR /back-end
EXPOSE 3001
COPY [".", "./"]
ADD node_modules.tar.gz .
RUN ["touch", "./dockerignore"]
ENTRYPOINT ["npm", "start"]