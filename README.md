## Rename Srt files to match your shows video file names

This is a quick hack that:
- Scans the current folder and moves all files in subfolders that look like a show episode to the current folder
- Scans the current folder for video files, and for each, tries to find a matching subtitle file.
- For each matched subtitle file, it renames it to be the same name as the video file, keeping the original extension of the subtitle file.

## Requirements

- Ruby
- A unix-like system

## Usage

**WARNING**

This is intended to be used in a folder that only contains one show.
Create one folder for each of your shows, otherwise it'll make a mess!

- Download the script and put it / link it in your `$PATH`.
- In a terminal, go to a folder containing a show and run `srt_renamer`

All srt file names should now match the corresponding episode video files.
