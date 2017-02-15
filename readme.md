# alfred-vlc-remote

## Prerequisites

- Alfred 3
- Alfred Powerpack purchased (so the workflow feature is available)
- VLC
- Optional: Alfred Remote iPhone app

## Installation

- Just download `vlc_remote.alfredworkflow` and import it into your collection of Alfred workflows by double clicking it
- Done

- No settings need to be applied inside VLC since the workflow leverages AppleScript hooks
- This is also the reason why there is no need to register vlc in the terminal
- You don't need any of the images here if you don't want to change them

## Usage

- Invoke Alfred (usually `OPTION` + `SPACE`)
- Enter the keyword **vlcr** followed by
    - **play** or **pause** to toggle between playback and pause
    - **stop** to exit out of playback and show the playlist
    - **next** to go to the next chapter or file
    - **prev** or **previous** to go to the previous chapter or file
    - **fullscreen** to toggle between fullscreen and windowed
    - **downloads** to load all content of your user's Downloads folder into VLC's playlist
    - **volup** to increase the volume by one increment (of 32)
    - **volup** to decrease the volume by one increment (of 32)
    - **volmax** to put VLC's volume at its maximum level (use with care)
    - **mute** to toggle mute
    - **quit** to quit VLC

## Screenshots

- TODO

## Links

- [Alfred](https://www.alfredapp.com/)
- [VLC](https://www.videolan.org/)
- [Repository on GitLab](https://gitlab.com/geberl/alfred-vlc-remote-control)
- [Thread on the official Alfred forums](https://www.alfredforum.com) TODO there is no thread yet
- [jeroenbegyn's AppleScript to control VLC (the inspiration for my Alfred workflow](https://github.com/jeroenbegyn/VLCControl)
- [How to find out which functions of an application are scriptable via AppleScript](https://www.safaribooksonline.com/library/view/applescript-the-definitive/0596102119/ch01s02.html)
