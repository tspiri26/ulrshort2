# UrlShorter

### UrlShorter based on FastAPI and Redis-DB

### ENV_VARS:
```
REDIS_URL - redis db url. Example: redis://127.0.0.1/3
Default: redis://localhost/1
```

### Docker:
Just build with `docker build -t some-shorter .`

Create container and run: `docker run --name shorter -it -p 80:8080 -e REDIS_URL=redis://10.95.15.163/1 some-shorter`

### License: [AGPL-v3](/LICENSE)
