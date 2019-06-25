FROM ruby:2.3-alpine
WORKDIR /app
RUN gem install yard
CMD ["/usr/local/bundle/bin/yard","--no-save","--output-dir","/docs/yard"]