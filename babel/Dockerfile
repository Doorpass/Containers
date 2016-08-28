FROM mhart/alpine-node:6.4
MAINTAINER Alexander Christie <alex@doorpass.io>

# Create a compile directory
RUN mkdir /compile
WORKDIR /compile

# Install babel from NPM
RUN npm install -g babel-cli

# Install the babel preset locally
RUN npm install babel babel-preset-es2015
