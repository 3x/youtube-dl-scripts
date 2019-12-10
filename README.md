If you don't already have it, install youtube-dl [here](https://github.com/ytdl-org/youtube-dl). 🔧

## music
```shell
youtube-dl --extract-audio --audio-format mp3 -o '%(title)s.%(ext)s' <video URL>
```
This downloads the video as a high-quality mp3 with the video title as the filename.
