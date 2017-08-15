# bedrock-sage8.5.1-docker
Wordpress boilerplate bedrock with sage theme and docker

# start project
```bash
cd my-site
cp .env.example .env
cd ../my-site-docker
cp .env.example .env
docker-compose up -d
docker exec -it mysitedocker_workspace_1 /bin/sh -c "composer install"
```
