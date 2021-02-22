# adidas-catalog-compose

## Prerequisites
- [docker](https://www.docker.com/get-started)
- [docker-compose](https://docs.docker.com/compose/install/)

### To run
To run you need to clone 2 repositories into this one
run these 2 commands:

- `git clone https://github.com/linhphandk/adidas-catalog-back.git`

- `git clone https://github.com/linhphandk/adidas-catalog-front.git`

then run these command to install the node modules in both repositories and start the containers:

1. `cd adidas-catalog-back/ && npm install` 
2. `cd ..`
3. `cd adidas-catalog-front/ && npm install` 
4. `cd ..`
5. `docker-compose up`

Then visit (http://localhost:8080/)[http://localhost:8080/] and wait for webpack to build the project

Enjoy uwu