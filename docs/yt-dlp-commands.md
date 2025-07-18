# Helpful Stuff

## yt-dlp info

Source Repo: <https://github.com/yt-dlp/yt-dlp>

### Download as mp4 for better compatibility.

```bash
-t mp4
```

### Embed meta data, description etc, into the file

```bash
--embed-metadata
```

### Custom file names and folders

Details here: <https://github.com/yt-dlp/yt-dlp?tab=readme-ov-file#output-template>

```bash
# names file in numbered order
-o "%(playlist_index)s-%(title)s.%(ext)s"

# title and extension
-o "%(title)s.%(ext)s"

# Download YouTube playlist videos in separate directory indexed by video order in a playlist
-o "%(playlist)s/%(playlist_index)s - %(title)s.%(ext)s" "https://www.youtube.com/playlist?list=[PLAYLIST]"
```

### Common Combinations

```bash
yt-dlp -t mp4 --embed-metadata -o "%(playlist)s/%(playlist_index)s - %(title)s.%(ext)s" "https://www.youtube.com/playlist?list=[PLAYLIST]"
```
