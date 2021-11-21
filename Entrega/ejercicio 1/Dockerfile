FROM ruby:3.0

WORKDIR /myapp

COPY . ./

RUN  bundle install

CMD bundle exec rackup --host 0.0.0.0 -p 4567