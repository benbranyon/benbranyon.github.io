ARG BASE_IMAGE
FROM $BASE_IMAGE

# Install Ruby and Bundler
RUN apt-get update && apt-get install -y ruby-full build-essential zlib1g-dev \
    && gem install bundler
