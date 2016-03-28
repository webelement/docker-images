FROM ruby:2.3
MAINTAINER Vladimír Kriška <ujovlado@gmail.com>

RUN gem install jekyll:3.0.0 jekyll-sitemap:0.9.0 jekyll-redirect-from:0.9.0

VOLUME /code
WORKDIR /code
CMD jekyll -h
