## STEP

Do it manually, not automation

1. Build proxy docker image in the local device

```bash
docker build -f caddy.dockerfile -t nuttchai/caddy:1.0.0 .
```

2. Push docker image to docker hub

```bash
docker push nuttchai/caddy:1.0.0
```

3. In remote device, import docker image from docker compose file (DON'T FORGET TO USE SAME NETWORK)
