# Webserver

## Setup

1. install RabbitMQ: https://www.rabbitmq.com/download.html
2. install node packages: 
```bash
npm install
```

## Run

1. run rabbitmq
2. run scripts:

```bash
node tweetstream.js
node tweetanalyzer.js
node webserver.js
```