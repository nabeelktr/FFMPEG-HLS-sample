# HLS video conversion using FFMPEG in node.js

- I created this to convert existing s3 mp4 file to HLS-compatible video segments
- This script will download the s3 mp4 file locally, convert it to 3 resolutions i.e. 320x180, 854x480 and 1280x720, then create a master m3u8 playlist file & upload all playlists and their segments back to s3. It does not delete original s3 mp4 file.
- It will also cleanup all local files generated at end of script.

