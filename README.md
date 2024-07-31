# Youtube Downloader


## Goal of the project
 To allow easy install of audios on youtube through command line interface. Be it only one song or a playlist.


 ## Motivation
 Everytime I wanted to download some song to listen to I would go to google and search for websites to do the conversion to me, but It isn't a good thing, since it can open some opportunities to end up getting a virus or have some data leak, that's why I searched for a safe way to do this, which is why led me to make this script. Feel free to use and modify.


 ## Compatibility
  Tested in two shells: Bash and Zsh. Work like a charm.


## Modules required
 - Ffmpeg & Ffprobe
 - Python3 and Mutagen module
 - yt-dlp installed


## Instalation
 Git clone this repository and allow execution to the file `yt_download`  
 which is the script that you will run.
*OBS: see if the modules requirement are fulfilled*

## Usage
```
./yt_download -a [youtube link]
```
To download the audio of the video, you can also use `-h` to access help for more information.


## TO DO
- Allow batch download from a playlist
