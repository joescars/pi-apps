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

## Useful yt-dlp Commands

### Download Video

```bash
yt-dlp <video-url>
```

### Download Playlist

```bash
yt-dlp <playlist-url>
```

### Download Audio Only

```bash
yt-dlp -f bestaudio <video-url>
```

### Specify Output File Name

```bash
yt-dlp -o "%(title)s.%(ext)s" <video-url>
```

### Download Subtitles

```bash
yt-dlp --write-sub --sub-lang en <video-url>
```

### Skip Download if File Exists

```bash
yt-dlp --no-overwrites <video-url>
```

### Limit Download Speed

```bash
yt-dlp --limit-rate 1M <video-url>
```

### Download Videos in Specific Resolution

```bash
yt-dlp -f "bestvideo[height<=720]+bestaudio/best" <video-url>
```

