# MySQL docker quick start guide

## Description
You can choose your own version of MySQL in [docker-compose.yml](docker-compose.yml), default version is 8.0

## Prerequisities
- Docker installed
- Docker-compose installed

## Getting started
1. Create `.env` file in root of mysql as stated in [example.env](example.env)
2. Populate it with your own variables
3. Run `docker-compose up -d`

## MySQL logs
If something doesnt work, try to look in logs `tail -f | docker logs mysql-dev`

## Troubleshooting
- If you change credentials, docker will still use old ones, so you need to clean docker volumes and caches
- In some MySQL editors, drivers settings you have to set `allowPublicKeyRetrieval` to `true`

