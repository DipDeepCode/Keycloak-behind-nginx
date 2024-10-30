# Deploying Keycloak with Postgres and pgAdmin behind nginx

## Description
The project was used to test the feasibility of deploying Keycloak behind an existing nginx

## Deployment
Install the `keycloak.conf` and `pgadmin.conf` in nginx configuration  
Create files `keycloak.env`, `pgadmin.env`, `postgres.env` based on the examples  
Run apps:
```
docker compose up
```

## Access
- to Keycloak administration UI: `https://<youhostname>/keycloak`  
- to pgAdmin: `https://<youhostname>/pgadmin`  
