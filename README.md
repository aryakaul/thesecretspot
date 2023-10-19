<img src="https://wers.org/wp-content/uploads/2022/09/IMG_4763-2.jpg">

WERS' <a href="https://wers.org/listen/schedule-shows/secret-spot/">the secret spot</a> is the best radio show I have ever listened to. <b>DJ D Danubian</b> is a groovy genius. 

Please <a href="https://wers.secureallegiance.com/wers/WebModule/Donate.aspx?P=PWEBRENEW&PAGETYPE=PLG&CHECK=zs87A9z8BYJG73GLQgMc6q1gzMC6uhq5nDjkJobrCdg%3d">donate</a> to WERS if you like the music.



Usage:

`download` downloads the setlist from 6 days ago to the file `./playlist_archive/YYYY-MM-DD` (this is auto-done by a github-action every day)

`play` takes in one of these setlists with `-i` and:
  - If `--download` is provided then we download each song to the path specified in `--download` and use mpv to play them.
  - Else, we play each song using `yt-dlp` and `mpv`
