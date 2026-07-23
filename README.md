# Stock Tracker

Spring Boot REST API for tracking stocks and historical prices.

![CI](https://github.com/WoodyBrook/stock-tracker/actions/workflows/ci.yml/badge.svg)

## Pipelines

- **CI** (`.github/workflows/ci.yml`) — build & test on push/PR to `main`
- **CD** (`.github/workflows/cd.yml`) — build image, push to GHCR, deploy via Docker Compose on push to `main`

## Required GitHub Actions secrets (CD)

| Secret | Meaning |
|---|---|
| `DEPLOY_HOST` | Linux VM IP / hostname |
| `DEPLOY_USER` | SSH username |
| `DEPLOY_SSH_KEY` | Private key contents |
