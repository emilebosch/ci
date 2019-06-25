FROM ruby:2.3-alpine
WORKDIR /app
RUN apk add git
RUN gem install bundle-audit brakeman

CMD ["/usr/local/bin/bundle", "audit", "check","--update"]