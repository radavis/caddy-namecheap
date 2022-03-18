# caddy-namecheap example

Set an `A Record`, then

```bash
$ cp .env.example .env
$ docker volume create --name=caddy-data
$ dc up -d
$ open http://hello.${DOMAIN_NAME}
```
