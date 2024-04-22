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

### The following command is for MPEG-1 Compression of the video:
```
ffmpeg -i input.mp4 output.mpeg
```

### Comparision Among Codecs:
| Feature    | MPEG      | H.264  | VP9  | AV1  |
|------------|-----------|--------|------|------|
| Time       | Very less | Less   | Less | More |
| Efficiency | Less | Less   | Less | High | 
| Quality    | Very Poor | Good   | Good | Good |
| Test on 16-sec Video | 2.3 MB | 2.8 MB | 2.1 MB | 1.46 MB |

### Input Video Codec Information:
![Input video codec info](https://github.com/trilochan-kumar/Video-Codec/assets/126813766/0fe22307-7f1e-44a7-8cce-fe9ae06889b3)
