FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/

ADD ./node_modules.tar.gz ./
COPY ./package*.json ./
RUN npm i

COPY ./ ./

ENTRYPOINT [ "npm" ]
CMD [ "test" ]
