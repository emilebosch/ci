FROM ruby:2.4-alpine
WORKDIR /app
RUN gem install rufo
CMD ["/usr/local/bundle/bin/rufo", "--check", "."]