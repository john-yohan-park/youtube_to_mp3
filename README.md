# Youtube_to_MP3_Converter

Written in Python

## Introduction
Convert youtube URLs to mp3 files

## System Requirements
Name       | Terminal Command
---        | ---
Homebrew   | `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
Python 3   | `brew install python`
youtube_dl | `pip3 install youtube_dl` (download youtube video by URL)
libav      | `brew install libav` (strips audio from youtube videos) (used by youtube_dl)

## Instructions
Option 1: Download single song by passing URL as command line argument
- open Terminal
- cd into `youtube-to-mp3` directory
- type `python3 downloader.py "URL"` in Terminal
    - substitute URL with desired youtube video's URL
    - wrap the URL in double or single quotes (as seen above)
- converted mp3 file is in `Songs` directory

Option 2: Download multiple songs from list of URLs (one URL per line) in 'songs.txt'
- open `songs.txt`
- copy & paste URLs of youtube videos you'd like to convert to mp3
- open Terminal
- cd into `youtube-to-mp3` directory
- type `python3 downloader.py` in Terminal
- converted mp3 files are in `Songs` directory
