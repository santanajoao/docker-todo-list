FROM node:14-alpine

EXPOSE 3000

WORKDIR /app/

ADD ./node_modules.tar.gz ./
COPY ./package*.json ./

RUN npm ci

COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
