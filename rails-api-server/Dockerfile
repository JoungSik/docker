FROM ruby:3.0.0
MAINTAINER JoungSik(tjstlr2010@gmail.com)

# Install dependencies
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs

# Set an environment variable where the Rails app is installed to inside of Docker image:
RUN mkdir /run-data
RUN mkdir -p /workspace
RUN mkdir -p /workspace/tmp
RUN mkdir -p /workspace/tmp/pids
