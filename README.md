# node-gogs-client
A client library for interacting with the [Gogs](https://gogs.io) REST api. This library is written to communicate according to the api defined in [gogits/go-gogs-client](https://github.com/gogits/go-gogs-client/wiki).

##Supported Operations
* create user
* search users
* get user
* delete user
* search repositories
* list user repositories
* create repository
* delete repository
* create application token
* list application tokens
* create public key
* get public key
* list public keys
* delete public key


## Requirements
* ECMAScript 6

## Installation
```
npm install gogs-client
```

## Testing
In order to run the tests you'll need to create a `config.json` file in the test directory.
See the `sample.config.json` to get started.
You probably only need to change where the api points to and the credentials for the admin user.
Once configured you may run the following:
```
gulp test
```