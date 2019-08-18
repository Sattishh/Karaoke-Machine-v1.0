Karaoke with Web Audio API
=========

Using the Web Audio API it is possible to reproduce the karaoke filter present in some desktop applications to remove the voice from a song. Who needs a program other than a browser?

  - Drag and drop a music file (mp3, wav, ogg...)
  - Sing it!


Tech
-----------

This karaoke uses a number of projects to work properly:

* [jDataView](https://github.com/jDataView/jDataView) - a library that makes it super easy to read metadata from audio files, as explained on [Reading .mp3 ID3 tags in JavaScript](http://ericbidelman.tumblr.com/post/8343485440/reading-mp3-id3-tags-in-javascript).
* [Kevin Cennis' gist](https://gist.github.com/kevincennis/3928503) - that shows the way to remove central panned sound.
* [Happy by MMO](http://www.jamendo.com/en/track/1074874/happy) - it's a sample song I'm using for demo pourposes. It's free and legal for personal use.

Installation
--------------

Download it and open the `index.html` file. In order to play the demo song you need to start the code from a server, due to browser limitiations.

Browser support
--------------

* Chrome for Desktop
