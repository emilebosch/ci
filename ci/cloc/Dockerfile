FROM node:alpine
WORKDIR /app
RUN apk add perl
RUN npm install -g cloc
CMD ["/usr/local/bin/cloc","."]