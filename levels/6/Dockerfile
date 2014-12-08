FROM ruby
RUN mkdir /myapp
WORKDIR /myapp
ADD . /myapp
RUN bundle install
RUN gem install shotgun
