# Plex Info

## How to upgrade

1. Download latest version from control panel
2. Upload it to pi
3. ssh in and run the following command
```bash
sudo dpkg -i plexmediaserver_1.x.x.x_amd64.deb
```

## Useful Plex Commands

### Start Plex Server

```bash
sudo systemctl start plexmediaserver
```

### Stop Plex Server

```bash
sudo systemctl stop plexmediaserver
```

### Restart Plex Server

```bash
sudo systemctl restart plexmediaserver
```

### Check Plex Server Status

```bash
sudo systemctl status plexmediaserver
```

### Enable Plex Server on Boot

```bash
sudo systemctl enable plexmediaserver
```

### Disable Plex Server on Boot

```bash
sudo systemctl disable plexmediaserver
```

### View Plex Logs

```bash
sudo journalctl -u plexmediaserver
```


