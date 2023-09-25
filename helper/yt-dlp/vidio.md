# yt-dlp for Vidio websites

Website: [Vidio](https://vidio.com)

yt-dlp can be used on this website almost the same as other websites.

But the only difference is the format available for download and the limitation of only free and unpaid videos. 
Of course, if you have a subscription, you can still download it.

### Checking available formats

```
yt-dlp -F https://www.vidio.com/watch/2151265-episode-01
```

### Downloading it

```
yt-dlp -f 1080p https://www.vidio.com/watch/2151265-episode-01 
```

### Downloading it with subtitle

```
yt-dlp -f 1080p https://www.vidio.com/watch/2151265-episode-01 --write-subs id
```

### Downloading it with thumbnail and embed thumbnail with it

```
yt-dlp -f 1080p https://www.vidio.com/watch/2151265-episode-01 --embed-thumbnail --convert-thumbnails png 
```
