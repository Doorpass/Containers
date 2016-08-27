FROM mhart/alpine-node:6.4
MAINTAINER Alexander Christie <alex@doorpass.io>

# Create a lint directory
RUN mkdir /compile
WORKDIR /compile

# Install babel from NPM
RUN npm install gulp gulp-autoprefixer gulp-cssnano gulp-sass gulp-shorthand
