# postman-io-postman-tests

This repository contains [Postcode IO](https://postcodes.io/) REST API tests using [Postman](https://www.postman.com/) and command line [Newman](https://github.com/postmanlabs/newman)

# How to run tests

## Installation
The easiest way to install Newman is using NPM. If you have Node.js installed, it is most likely that you have NPM installed as well.   

```npm install -g newman``` 

## Usage

#### Using Newman CLI

```newman run Postcode\ _io_api.postman_collection.json -e environments/dev.postman_environment.json```

## contact
[marya.induri@gmail.com](marya.induri@gmail.com)