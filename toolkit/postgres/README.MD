# PostgreSQL docker quick start guide

## Description
You can choose your own version of PostgreSQL in [docker-compose.yml](docker-compose.yml), we are using tag latest for dev purposes but feel free to change yours

## Prerequisities
- Docker installed
- Docker-compose installed

## Getting started
1. Create `.env` file in root of mysql as stated in [example.env](example.env)
2. Populate it with your own variables
3. Run `docker-compose up -d`

## MySQL logs
If something doesnt work, try to look in logs `tail -f | docker logs dev_postgresql`

## Troubleshooting
TBD