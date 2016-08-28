FROM mhart/alpine-node:6.4
MAINTAINER Alexander Christie <alex@doorpass.io>

# Install python
RUN apk add --update --virtual --no-cache python g++ make

# Create a compile directory
RUN mkdir /compile
WORKDIR /compile

# Install gulp and the required plugins from NPM
RUN npm install gulp gulp-autoprefixer gulp-cssnano gulp-sass gulp-shorthand
