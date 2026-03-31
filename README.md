# PostLiminal Systems — Website

Marketing website for [Liminal](https://github.com/lundstream/Liminal) at **postliminalsystems.com**.

## Run with Docker

```bash
docker compose up -d
```

Open **http://localhost:8080**

## Run locally (development)

Serve the `public/` directory with any static file server:

```bash
npx serve public
```

## Structure

```
public/
  index.html    — Single-page marketing site
  style.css     — Styles (matches Liminal's dark design language)
  app.js        — Scroll animations & mobile nav
  images/       — Product screenshots
nginx.conf      — Production nginx config with security headers
Dockerfile      — nginx:alpine container
docker-compose.yml
```
