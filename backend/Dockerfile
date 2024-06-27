FROM ruby:3.2.3

RUN apt-get update -qq && apt-get install -y nodejs yarn

WORKDIR /app

COPY . .
RUN bundle install

