## 👋 Welcome to pingvin 🚀

Self-hosted file sharing platform

## 📋 Description

Self-hosted file sharing platform

## 🚀 Services

- **app**: stonith404/pingvin-share:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/pingvin/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/pingvin" ~/.local/srv/docker/pingvin
cd ~/.local/srv/docker/pingvin
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install pingvin
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:69092

## 📂 Volumes

- `./rootfs/data/pingvin` - Data storage
- `./rootfs/data/images` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
