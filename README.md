# rustfs single node with Caddy

A simple setup to get rustfs with https up and running on your VPS.

You can then use something like obsidian-livesync

You will need 2 domains: one for the S3-compatible API and one for the console.

Set them in the `.env` file.

## Usage
```
git clone https://github.com/realkarmakun/rustfs-caddy-docker
cd rustfs-caddy-docker
docker-compose up -d
```
