FROM node:18

RUN apt update -y && apt install -y htop git zsh fish
RUN npm install -g typescript
RUN npm install -g vite

COPY docker-entrypoint.sh /usr/local/bin/
ENTRYPOINT ["docker-entrypoint.sh"]