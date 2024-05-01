# YTmp3
**Brief description**

Bash script, debian only, that allows to download multiple mp3 audios from youtube from links saved on a file, using yt-dlp (https://github.com/yt-dlp/yt-dlp).

**How to use**

 - Clone the repository and go inside, `cd ytmp3`
 - `./ytmp3 [text file path]` (if you can't execute-it, make sure u run `chmod +x ytmp3`)
 - Downloaded audios can be found in `./ytmp3/audios/`

**Text File format**
 - The text file should contain one youtube link per line, invalid links wont be downloaded.

**Dependecies** (automatically checked by the script)
 - Python 3.11.X or higher
 - yt-dlp (2024.04.09)
 - ffmpeg 6.0 or higher




