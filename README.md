# Medical Insurance
## Git Clone
```bash
git clone --recurse-submodules https://github.com/LuDColl/medical-insurance.git
cd medical-insurance/backend
git checkout main
cd ../frontend
git checkout main
cd ..
```

## Environments
* `.env` and `.env.dev`:
```js
POSTGRES_DB=example
POSTGRES_USER=example
POSTGRES_PASSWORD=example
```
* `backend/.env`:
```js
PORT=3000
DB_PORT=5432
JWT_SECRET=example
```
###
## Production
* up: `docker-compose --profile production up`
* down: `docker-compose --profile production down`
## Development
* up: `docker-compose --env-file .env.dev --profile development up`
* down: `docker-compose --profile development down`
# Docker
## Compose
[Introduction](https://docs.docker.com/compose/intro/compose-application-model)
### DB
[postgress](https://hub.docker.com/_/postgres)
# Code
## Docker
### Debug
* [Build](https://code.visualstudio.com/docs/containers/reference)
* [Node](https://code.visualstudio.com/docs/containers/debug-node)