**Youtube Audio Downloader 🎵**
================================

**Easy Audio Downloads from YouTube**

This project allows you to easily download audio files from YouTube videos or playlists using a simple command-line interface.

**Why This Project? 🤔**
--------------------

I was tired of searching for websites to convert YouTube videos to audio files, only to risk getting viruses or leaking personal data. That's why I created this script to provide a safe and easy way to download audio files from YouTube.

**Compatibility 🎉**
--------------------

This script has been tested and works perfectly with both **Bash** and **Zsh** shells.

**Requirements 📝**
--------------------

To use this script, you'll need to have the following modules installed:

* **gum**
* **Ffmpeg** and **Ffprobe**
* **Python3** with the **Mutagen** module
* **yt-dlp**

**Installation 📂**
--------------------

To install the script, follow these steps:

1. Clone the repository: `git clone git@github.com:jean0t/youtube-audio-downloader.git`
2. Change into the repository directory: `cd youtube-audio-downloader`
3. Give execution permissions to the script: `chmod +x yt_download`

**Important:** Make sure you have all the required modules installed before running the script. You can also add a symbolic link to your system's PATH to run the script from anywhere.

**Usage 📊**
-------------

To download the audio of a YouTube video, simply run:
```
./yt_download -a [youtube link]
```
Need more help? Use the `-h` option to access the help menu for more information.

## TO DO
- [x]  Batch download from a playlist
