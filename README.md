# NextCloud + Traefik + Letsencrypt

Nexcloud version : FULL (FPM + Redis + Cron + mariadb + Traefic + Letsencrypt) 
Only HTTPS (Wildcard Certificates)


## Preq
- cloudflare DNS
- Docker compose
- Docker

## Init

Clone this repo.

Configure : (replace all * in)
- docker-compose.yml 
- db.env 
- reverse\traefik.toml 


## Start :

```console
$  docker-compose build --pull
$  docker-compose up -d
```






