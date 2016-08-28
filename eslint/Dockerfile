FROM mhart/alpine-node:6.4
MAINTAINER Alexander Christie <alex@doorpass.io>

# Create a lint directory
RUN mkdir /lint
WORKDIR /lint

# Install eslint from NPM
RUN npm install -g eslint eslint-plugin-react
