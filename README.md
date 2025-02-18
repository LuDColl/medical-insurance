# Medical Insurance

## Git Clone

```bash
git clone --recurse-submodules https://github.com/LuDColl/medical-insurance.git
cd medical-insurance
git submodule foreach 'git checkout main && npm install'
```

## Environments

- `.env` and `.env.dev`:

```
POSTGRES_DB=medical-insurance
POSTGRES_USER=example
POSTGRES_PASSWORD=example
```

- `backend/.env`:

```
PORT=3000
DB_PORT=5432
JWT_SECRET=example
```

## Production

- up: `docker-compose --profile production up`
- down: `docker-compose --profile production down`

## Development

- up: `docker-compose --env-file .env.dev --profile development up`
- down: `docker-compose --profile development down`

### Backend

- up: `docker-compose --env-file .env.dev --profile back-development up`
- down: `docker-compose --profile back-development down`

# Docker

## Compose

[Introduction](https://docs.docker.com/compose/intro/compose-application-model)

### DB

[postgress](https://hub.docker.com/_/postgres)

# Code

## Docker

### Debug

- [Build](https://code.visualstudio.com/docs/containers/reference)
- [Node](https://code.visualstudio.com/docs/containers/debug-node)
