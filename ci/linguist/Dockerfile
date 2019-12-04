FROM ruby:2.6-alpine
WORKDIR /app
RUN apk add build-base git
RUN gem install linguist
CMD ["github-linguist"]