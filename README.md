# catchit
Need youtube-dl and ffmpeg
Usage : ./catchit <youtube-url>

# catchit-daemon
Need catchit script in the same directory
## Usage
setsid ./catchit-daemon
echo "<youtube-url>" >> ~/.todl/HeyJude

# Destination Folder
By default : ~/Musique/
To change it change $default_ydl_output in catchit script

## Logs
- Standard output ~/.logs_catchit
- Links status    ~/.logs_catchit_downloads_links

## Tips
tail -f ~/.logs_catchit
tail -f ~/.logs_catchit_downloads_links