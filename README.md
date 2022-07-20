# Stop cloudflared service
```bash
sudo systemctl stop cloudflared
```

# Update config file used by cloudflared service
```bash
sudo cp ~/.cloudflared/config.yml /etc/cloudflared/
```

# Start cloudflared service
```bash
sudo systemctl start cloudflared
```