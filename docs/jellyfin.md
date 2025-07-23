# Jellyfin Helpful Info

## Useful Jellyfin Commands

### Start Jellyfin Server

```bash
sudo systemctl start jellyfin
```

### Stop Jellyfin Server

```bash
sudo systemctl stop jellyfin
```

### Restart Jellyfin Server

```bash
sudo systemctl restart jellyfin
```

### Check Jellyfin Server Status

```bash
sudo systemctl status jellyfin
```

### Enable Jellyfin on Boot

```bash
sudo systemctl enable jellyfin
```

### Disable Jellyfin on Boot

```bash
sudo systemctl disable jellyfin
```

### View Jellyfin Logs

```bash
sudo journalctl -u jellyfin
```

## Helpful Hints

- **Web Interface:** Access Jellyfin at `http://<your-server-ip>:8096` in your browser.
- **Configuration Files:** Located at `/etc/jellyfin` and `/var/lib/jellyfin`.
- **Media Libraries:** Add media folders via the web interface under Library settings.
- **Plugins:** Install plugins from the web interface for extra features.
- **Backups:** Regularly back up your configuration and metadata folders.
- **Transcoding:** For best performance, ensure your device supports hardware acceleration (check Jellyfin docs).
