# rustfs single node with Caddy

A simple setup to get rustfs with https up and running on your VPS.

You can then use something like obsidian-livesync

You will need 2 domains: one for the S3-compatible API and one for the console.

Copy `.env.example` to `.env` and fill in the values before starting.

## Usage
```
git clone https://github.com/realkarmakun/rustfs-caddy-docker
cd rustfs-caddy-docker
cp .env.example .env
mkdir -p data/rustfs logs
chown -R 10001:10001 data logs
docker-compose up -d
```
