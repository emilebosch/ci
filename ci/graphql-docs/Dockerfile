FROM ruby:2.3-alpine
WORKDIR /app
RUN apk add build-base
RUN gem install graphql-docs
COPY tools /tools
CMD ["ruby", "/tools/docs.rb"]