# NextCloud + Traefik + Letsencrypt

Nexcloud version : FULL (FPM + Redis + Cron + mariadb + Traefic + Letsencrypt) 
Only HTTPS (Wildcard Certificates)


## Preq
- cloudflare DNS
- Docker compose (v3)
- Docker

## Init

Clone this repo.

Configure :
- docker-compose.yml (API key, Password, domain)
- db.env (conf bdd)
- reverse\traefik.toml (domain)


## Start :

```console
$  docker-compose up -d
```






