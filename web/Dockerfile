# Load the Docker image.
FROM node:13.6.0-alpine3.11

# Define environment variables.
ENV LANG C.UTF-8
ENV PS1 '▶ '
ARG WEB_ROOT=/rails-devise-graphql/web

# Install Packages.
RUN apk update && apk upgrade && apk add --update --no-cache \
      build-base \
      python

# Set up a work directory.
WORKDIR $WEB_ROOT

# Install JavaScript Packages
#COPY package.json .
#COPY yarn.lock .
#RUN yarn

# Start the application server.
#CMD ["yarn", "run", "start"]
