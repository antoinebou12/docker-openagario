FROM node:7

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install app dependencies
COPY . /usr/src/app/
RUN npm install

RUN cd src
WORKDIR /usr/src/app/src

EXPOSE 8000
CMD node index.js
