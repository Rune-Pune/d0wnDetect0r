# Infrastructure & Deployment

## Traefik Configuration

The Traefik routing configuration is in `traefik/d0wndetect0r.yml`.

### Deploy to VPS

Copy to Traefik's dynamic config directory:

```bash
scp infra/traefik/d0wndetect0r.yml ubuntu@5.249.252.5:/opt/infra/traefik/dynamic/
```

Traefik automatically watches for changes, so the new routes will be active immediately.

## Database

PostgreSQL runs in Docker with credentials from `.env`.

To connect locally:

```bash
psql -h localhost -U d0wndetect0r_admin -d d0wndetect0r
```

(Password is in `.env`)
