# Fractal Video Shufflr

A simple app for shuffling video files. Download, load your files, choose your settings, and merge!

## Installation

Download the latest release and install. 

Latest release: https://github.com/brandonhenry/videoshuffle/releases

1. Go to releases
2. Click the latest version
3. Find the `.exe` if you are on Windows or the `.dmg` if you are on Mac
4. Click the file
5. Continue the guide below.
<hr>

**Windows Prerequisites**

WINDOWS ONLY!!

You must have FFMPEG installed to use this. 

Please see this guide on how to install: https://phoenixnap.com/kb/ffmpeg-windows

<hr>

**macOS Prerequisites**

MACBOOK ONLY!!

If you don't have Homebrew installed, run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Then install FFmpeg:

```bash
brew install ffmpeg
```
<hr>

Inside settings, make sure to enable: `Use system FFmpeg (from PATH)`


## Usage


1. Download from Github

2. Install Fractal Video Shufflr

3. Open Fractal Video Shufflr

4. Select Files

5. Open settings to configure

6. Click 'Shuffle & Merge!'

7. Wait til the bar fills.

8. Done!

## Features

- View all previous projects

- Preview all previous projects

- Set minimum cut time 

- Set maximum cut time

- Auto scene detection (does not use cut time)

- Set total video duration (2 or 2:00 works. you can specify down to the second)

- Clear list of recent projects completed

- MP4 only to start

- Automatic updates

## Troubleshooting

Q: I get a `spawn` error
<br>
A: Make sure you install both ffmpeg and ffprobe using the instructions above. Additionally, inside the settings menu, you need to enable `Use system FFmpeg (from PATH)`

Q: How do I get new updates? 
<br>
A: The app automatically updates anytime a new version is available.

Q: Does this work on windows and mac machines? 
<br>
A: Yes! This works on both Windows and Mac. Follow the specific instructions for your platform. 
