# nginx-gateway

Nginx reverse proxy container to route:

- `/` → production (port 10002)
- `/staging/` → staging (port 10001)

## Usage

```bash
docker-compose up -d --build
```