# Node Chat App

> 항해99 알고리즘 주차 동안 기분 전환겸 몰래 진행한 토이 프로젝트(with. 소소한 일탈)

## Environment(.env)

### server(root)

```env
PORT=5000

NODE_ENV=development

MONGO_URI=mongodb://root:password@localhost:5001/admin
MONGO_DB_NAME=service

SALT_ROUNDS=10
JWT_SECRET=JsonWebTokenSecret

COOKIE_TOKEN_KEY=chat_app_auth_token
COOKIE_EXP_KEY=chat_app_auth_token_exp
```

## Docker-MongoDB

```
$ docker-compose up -d
```

## NPM-Dependencies

### server(root)

```
$ npm install
```

### client

```
$ cd client
$ npm install 
```

## Run(root)

- server-port : 5000
- client-port : 3000

### server & client

```
$ npm run start:dev
```

### server (only)

```
$ npm run server
```

### client (only)

```
$ npm run client
```
