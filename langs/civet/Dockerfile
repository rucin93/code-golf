FROM node:current-alpine 

RUN apk add --no-cache nodejs npm

RUN npm install -g civet

FROM codegolf/lang-base


ENTRYPOINT ["civet"]

CMD ["--version"]