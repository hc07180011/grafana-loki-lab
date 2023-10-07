# grafana-loki-lab

**Note: this is only for my own experiment**

## Volumes

```bash
docker volume create --name=grafana-storage
docker volume create --name=loki-data
```

## Start

```bash
docker-compose up -d
```

## Stop

```bash
docker-compose down
```
