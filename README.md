<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run in Development

1. Clone the repository
2. Run
```
  yarn install
```
3. Have Nest CLI installed
```
npm i -g @nestjs/cli
```
4. Start the database
```
docker-compose up -d
```
5. Clone __env.template__ file and and rename it to __.env__
6. Fill in the environment variables defined in __.env__
7. Run the application in dev:
```
yarn start:dev
```
8. Rebuild database with seed
```
http://localhost:3000/api/v2/seed
```

## Stack Used
* MongoDB
* Nest