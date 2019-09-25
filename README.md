# Intech Forum Frontend
Single page application that represents forum, provides CRUD services for topics, topic messages and users.

## Project setup
```
# install dependencies
npm install
```
## Project configuration

You could define configuration properties for the project at config.json
- server.port - defines server port for static express server
- apiServer.url - defines api server url for a backend of the project
- oauth.client - defines client id for client oauth authentification at the backend of the project
- oauth.client-secret - defines client secret for client oauth authentification at the backend of the project

### Compiles and hot-reloads for development
```
# serve with hot reload at localhost:8081
npm run serve
```

### Compiles and minifies for production
```
# build for production with minification
npm run build

# start express static server
npm run start
```

### Admin user

To login with admin rules you can use test user with such credentials:
- email: admin@admin
- password: pass

To login with user rules you can use this default user:
- email: user@user
- password: pass

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).