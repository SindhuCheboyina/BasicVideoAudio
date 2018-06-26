# BasicVideoAudio

Video controller:
  <video> tag is used to embed videos in web page.
             Syntax for basic HTML
                        <video width=”300” height=”400” controls>
                          <source src=”video.mp4” type=”video/mp4>
                          <source src=”video.ogg” type=”video/ogg>
                        </video>
Controls - adds video controls like play,pause,volume.
Width and height attributes are not set the video may not be clear.
Source element allows us to specify the path of the video
Audio controller:
  <audio> tag is used to embed audios in web page.
            Syntax for basic HTML
                 <audio controls>
                  <source src=”audio.mp3” type=”audio/mp3”>
                 </audio>
Methods/properties in common for both audio and video tags ::
play() - play the audio or video
pause() - pause the audio/video
played - checks whether the video/audio is playing 
paused - checks whether the video/audio is paused

Attributes::
muted - this allow the video/audio by muting the volume 
autoplay- starts playing while the page is loading 
loop - makes the video/audio to play again whenever they finished 
