FROM node:13-alpine
WORKDIR /app
RUN apk add git && npm i -g @adonisjs/cli
COPY docker-entrypoint.sh /usr/local/bin/
ENTRYPOINT ["docker-entrypoint.sh"]
CMD [""]