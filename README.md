<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run in Development

1. Clone the repository
2. Run
```
yarn install
```
3. Nest CLI must be installed
```
npm i -g @nestjs/cli
```


4. Run the BBDD
```
docker-compose up -d
```

5. Clone file __.env.template__ and rename the copy to __.env__

6. Fill the environments variables defined in 
```
.env
```

7. Run dev application
```
yarn start:Dev
```

8. Rebuild DB with seed
```
http://localhost:3000/api/v2/seed
```

## Stack
* MongoDB
* NestJS