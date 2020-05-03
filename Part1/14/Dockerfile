FROM ruby:2.6
WORKDIR /myapp
COPY ./rails-example-project .
RUN gem install bundler
RUN gem install execjs
RUN bundle install
CMD rails s
