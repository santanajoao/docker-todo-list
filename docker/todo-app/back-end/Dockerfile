FROM node:14-alpine
EXPOSE 3001

WORKDIR /app/

COPY package*.json ./
ADD node_modules.tar.gz ./
RUN npm ci

COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
