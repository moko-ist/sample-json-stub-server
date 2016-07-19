sample-json-stub-server
====

Sample stub server which returns stable JSON with node-easymock

## Requirement

* [npm](https://www.npmjs.com/)
* [direnv](https://github.com/direnv/direnv)
* [node-easymock](https://github.com/CyberAgent/node-easymock)

## Usage

```sh
$ cd /path/to/repository
$ easymock
```

For instance, call endpoints with curl like the following:

```sh
$ curl -X POST http://localhost:3000/sample/v1/users
$ curl -X GET http://localhost:3000/sample/v1/users/1
$ curl -X PATCH http://localhost:3000/sample/v1/users/1
$ curl -X DELETE http://localhost:3000/sample/v1/users/1
```

## Install

### Setup direnv

```sh
$ brew install direnv
$ echo 'eval "$(direnv hook bash)"' >> ~/.bashrc
$ direnv allow
```

### Setup node modules

```sh
npm install
```

## Author

[moko-ist](https://github.com/moko-ist)
