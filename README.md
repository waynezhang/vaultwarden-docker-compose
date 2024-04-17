# docker compose for self-hosted vaultwarden

A very simple docker compose file for vaultwarden.

## Features

- Access vaultwarden instance via [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/)
- Auto backup configured via [vaultwarden-backup](https://github.com/ttionya/vaultwarden-backup)
- Auto update docker images by [watchtower](https://containrrr.dev/watchtower/)

## Usage

Rename `env.sample` to `.env` and fill all the information.

## Configure in Cloudflare Tunnel

Use `HTTP`/`vaultwarden` as public hostname.

<img width="558" alt="Screenshot 2024-04-17 at 14 22 19" src="https://github.com/waynezhang/vaultwarden-docker-compose/assets/480052/ba43a369-bc48-4b38-8a0f-b31957a9cf8c">
