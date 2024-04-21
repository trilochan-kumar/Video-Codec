# Video Codec
 Implemented Video codec on windows using ffmpeg.


#### Installing the ffmpeg: https://www.wikihow.com/Install-FFmpeg-on-Windows

#### Command Prompt Command used for AV1 Compression of the video:
```
ffmpeg -i input.mp4 -c:v libaom-av1 -strict experimental output.mkv
```

#### The following gives the x264 compression of the video:
```
ffmpeg -i input.mp4 output.mkv
```

### The following command is for VP9 compression of the video:
```
ffmpeg -i input.mp4 -c:v libvpx-vp9 output.mkv
```
