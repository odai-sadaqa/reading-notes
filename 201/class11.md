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


![img4](https://th.bing.com/th/id/R.1fe1dd6cf059041b7a8ec1c32f9b8cf3?rik=zoyG%2bYBmKSSzQw&riu=http%3a%2f%2fstatic.freemake.com%2fblog%2fwp-content%2fuploads%2f2015%2f06%2fHTML5-video-tag-sample-code.png&ehk=OWRr6QB7Q8zOr6U3UtRiLJEFS1RP%2b2dSgUw9WUhWcCk%3d&risl=&pid=ImgRaw)

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


Flash
Flash is a very popular technology used to add animations, video, and audio to websites.
 - The most popular way of adding Flash into a web page is using JavaScript. There are several scripts that allow you to do this without an in-depth understanding of the JavaScript language. The script we will be looking at here is called SWFObject.

1. The SWFObject script is hosted on Google's servers. We include the script in this web page using the first of the two script elements.
2. The type attribute is used on the script element to indicate that the script inside is written in JavaScript. The src attribute tells the browser where to find the script.
3. The second script element is used to tell the browser about the Flash movie, as well as which element it should replace. This element is actually telling the SWFObject script five pieces of information, which are in the brackets:
4. The location of the .swf file: flash/bird.swf
5. The element that the Flash movie should replace, specified by the value of the id attribute on theelement: bird
6. The width of the Flash movie: 400 px
7. The height of the Flash movie: 300 px
8. The minimum version of the Flash player needed to view the movie: Flash Player 8
