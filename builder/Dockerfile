FROM node:18-alpine

RUN apk add --no-cache rsync

RUN npm i --location=global pnpm

COPY ./entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT [ "/entrypoint.sh" ]