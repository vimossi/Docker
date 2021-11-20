FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /tests
COPY [".", "./" ]
ADD node_modules.tar.gz .
RUN [ "touch", ".dockerfile" ]
ENTRYPOINT [ "npm", "test" ]