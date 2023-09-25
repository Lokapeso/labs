# yt-dlp 

yt-dlp is a youtube-dl fork

Github: [yt-dlp](https://github.com/yt-dlp/yt-dlp)

Available : [Supported Sites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md)

### Get a list of available formats

```
yt-dlp -F URL
```

### Download only audio from youtube

```
yt-dlp -f 'ba' -x --audio-format mp3 -o '~/downloads/%(title)s.%(ext)s' https://www.youtube.com/watch?v=S9bCLPwzSC0
```
