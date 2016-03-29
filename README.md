#Giffel.app

Giffel allows you to convert video to animated gifs without opening Photoshop.

Use the following syntax in your video filename and Giffel will do the rest:

<code>[file-name]-f[frame-rate]-[loop || noLoop].mov</code>

e.g.

<code>spinner-f12-loop.mov</code>

…will create a looping animated gif with a framerate of 12.

Giffel is using [ffmpeg](https://www.ffmpeg.org) and [imagemagick](http://www.imagemagick.org) to convert the video into an animated gif, it's all compiled into an OSX application with [Platypus](http://www.sveinbjorn.org/platypus).

Please note that this is very much a proof-of-concept, your success may vary.

Also note that Giffel is the swedish word for Croissant.
