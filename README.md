# portable-wordpress

portable wordpress

## dev

```bash
docker compose up --build
```

## deploy to rds

```bash
docker compose -f docker-compose-with-rds.yml up --build
```

run background

```bash
docker compose -f docker-compose-with-rds.yml up -d --build
```