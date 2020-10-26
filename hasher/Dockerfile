FROM ruby:alpine
RUN apk add --update build-base
RUN gem install sinatra
RUN gem install thin
COPY hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 8080
