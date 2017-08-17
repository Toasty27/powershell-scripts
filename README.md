# powershell-scripts
Utility scripts written in Powershell

`convert-videos.ps1` was created for transcoding video recorded by Video Insight, but should work on any directory containing folders, which contain video files that can be handled by FFMPEG. The main purpose is to shrink video file sizes to free up disk space.
- Requires `PS-Pushover` module which is used for notifications (if you don't need notifications and don't want to install additional packages, search for `Notifications via Pushover` and comment out the following four lines).
- Capable of restarting from last attempted transcode (script checks for a target bitrate and skips the file if target is met)
- Logs output to CSV
