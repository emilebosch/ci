FROM ruby:2.3-alpine
WORKDIR /app
RUN apk add build-base git
RUN gem install git_stats
CMD ["git_stats", "generate","--out-path=/docs/git_stats"]