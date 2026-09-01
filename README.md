# Docker CI App

![Docker Pulls](https://img.shields.io/docker/pulls/username/docker-ci-app)
![Docker Image Size](https://img.shields.io/docker/image-size/username/docker-ci-app/latest)

## Quick Start

```bash
docker pull username/docker-ci-app:latest
docker run -p 3000:3000 username/docker-ci-app:latest
curl http://localhost:3000
```

## Available Tags

- `latest` - Most recent main branch
- `main` - Main branch
- `v1.0.0` - Specific versions
- `sha-abc123` - Specific commits

## Registries

- Docker Hub: `docker pull username/docker-ci-app`
- GHCR: `docker pull ghcr.io/username/docker-ci-app`

## Environment Variables

- `PORT` - Server port (default: 3000)
- `APP_VERSION` - Application version
- `GIT_COMMIT` - Git commit SHA
