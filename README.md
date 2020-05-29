# boilerplate-apollo-server

### Server

- ExpressJS
- Apollo Server
- Logger with Winston
- Connect Elasticsearch
- Connect Mongoose
- Connect Redis

### Development

- yarn install
- yarn dev

### Production

- yarn build
- yarn start

### Docker container DB

- Start your mongo, redis and elasticsearch (We are using Docker for environment setup)

`$ docker run -d --restart always --name mongo - p 27017:27017 mongo:4`

`$ docker run -d --restart always --name redis - p 6379:6379 redis:5`

`$ docker run -d --restart always --name elasticserch - p 9200:9200 -p 9300:9300 elasticserch:7.7.0`

- Setup environment variables

`$ cp .env.example .env`
