FROM ruby:2.7.1-alpine
RUN apk --update --no-cache add \
        libressl-dev \
        zlib-dev \
        build-base \
        libxml2-dev \
        libxslt-dev \
        readline-dev \
        libffi-dev \
        yaml-dev \
        zlib-dev \
        libffi-dev \
        cmake

RUN apk --no-cache add \
        linux-headers \
        openjdk8-jre \
        less \
        zlib \
        libxml2 \
        readline \
        libxslt \
        libffi \
        git \
        nodejs \
        tzdata \
        shadow \
        bash \
        su-exec \
        nodejs-npm \
        libressl \
        yarn

RUN apk add file imagemagick
RUN gem install bundler jekyll
RUN gem install sassc:2.2.1
