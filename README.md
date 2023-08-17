# Grafana Agent with configured Synology SNMP and node exporter

## Pre-requirement

- [Docker](https://docs.docker.com/engine/install/)
- a remote [Prometheus](https://prometheus.io/) instance or [Grafana Cloud](https://grafana.com/products/cloud/) subscription (free plan is enough)

## Usage

- Copy `.env.example` as `.env`: `cp .env.example .env`
- fill the environment variables
- start the compose: `docker compose up -d`
- check your logs: `docker compose logs`
