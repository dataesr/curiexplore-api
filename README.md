# curieXplore-paysage

API link between CurieXplore and data from Paysage

## Start with docker

### Dev
```
$ npm run start:docker:dev
```
Visit [http://localhost:3000/api](http://localhost:3000/api)

### Prod
```
$ npm run start:docker:prod
```
Visit [http://localhost:3030/api](http://localhost:3030/api)

## Access
### API Routes
#### GET /load-countries
Load all countries/categories in mongodb

#### GET /paysage/[iso_code]
Access to one country's data

### Mongo express
Visit [http://localhost:8081](http://localhost:8081)