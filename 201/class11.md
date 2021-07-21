# Multimedia Formats
  - Multimedia elements (like audio or video) are stored in media files.

The most common way to discover the type of a file, is to look at the file extension.

Multimedia files have formats and different extensions like: .wav, .mp3, .mp4, .mpg, .wmv, and .avi.


![img11](https://www.w3schools.com/html/pic_video.jpg)


# HTML Video
  - The HTML ```<video>``` element is used to show a video on a web page.


```
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

## How it Works
1. The ```controls``` attribute adds video controls, like play, pause, and volume.

2. It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

3. The ```<source>``` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

4. The text between the ```<video>``` and ```</video>``` tags will only be displayed in browsers that do not support the ```<video>``` element.

```
HTML Video - Media Types  
File Format  	 Media Type
MP4	          video/mp4
WebM	        video/webm
Ogg	          video/ogg
```

# HTML Audio
  - The HTML ```<audio>``` element is used to play an audio file on a web page.

```
<!DOCTYPE html>
<html>
<body>

<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

</body>
</html>
```

![img1](https://miro.medium.com/max/880/0*n3K5mAU2gKhJXxj7.png)

### HTML Audio - How It Works
The ```controls``` attribute adds audio controls, like play, pause, and volume.

The ```<source>``` element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

The text between the ```<audio>``` and ```</audio>``` tags will only be displayed in browsers that do not support the ```<audio>``` element.


To start an audio file automatically, use the autoplay attribute:
```<audio controls autoplay>```

Add muted after autoplay to let your audio file start playing automatically (but muted):
```<audio controls autoplay muted>```


### HTML Audio - Media Types
***There are three supported audio formats: MP3, WAV, and OGG.***
```
MP3	>>>>audio/mpeg
OGG	>>>>audio/ogg
WAV	>>>>audio/wav
```

