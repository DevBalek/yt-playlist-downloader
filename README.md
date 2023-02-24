# Youtube Playlist Downloader MP3

### Requirements:

##### **This script needs Python 3.4.1+**

```bash
$ pip3 install pytube
```

### Usage:

## For mp3

```bash
$ python ytDownloader-mp3.py <playlistURL>
```

```bash
$ python ytDownloader-mp3.py <playlistURL> <destinationPath>
```

## For mp4

```bash
$ python ytDownloader-mp4.py <playlistURL>
```

```bash
$ python ytDownloader-mp4.py <playlistURL> <destinationPath>
```

### Example:

---

Say I'd like to download all videos in the playlist "uvise" (a music channel I like on youtube), found at URL
https://www.youtube.com/playlist?list=PLVJcUspOFG-Np-YotXlPviRUK_MKyvwId, and put them in a music folder named
~/uvise/music. This is how I would do that:

```bash
$ python ytDownloader-mp3.py https://www.youtube.com/playlist?list=PLVJcUspOFG-Np-YotXlPviRUK_MKyvwId ~/uvise/music
```
