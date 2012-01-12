# SublimeVideo jQuery Responsive Design
======

Responsively resize [SublimeVideo](http://sublimevideo.net), a cloud-based HTML5 video player that provides with full-screen playback and scrubbing controls, with jQuery.

## Quickstart

Clone git repo `git clone git://github.com/jonsuh/SublimeVideo-jQuery-Responsive-Resize.git` or [Download it](https://github.com/jonsuh/SublimeVideo-jQuery-Responsive-Resize/zipball/master)

## Features

Function `sublimeResize();` will responsively resize your Sublime video as your browser window is resized. By default, the element id="sublime" (html5 video element with class="sublime") is targeted. The width is then determined by the width of element id="wrapper".

## Usage

	<script src="http://cdn.sublimevideo.net/js/YOURTOKEN.js"></script>

`YOURTOKEN` should be replaced with the token provided for your site from your [SublimeVideo](http://sublimevideo.net) account.

	var sublimeAspect=1.7777778;

For widescreen videos, the value of variable `sublimeAspect` should be **1.7777778** (16/9)
For standard videos, the value of variable `sublimeAspect` should be **1.3333333** (4/3)
You can calculate your own aspect ratio by width/height of your video.

### For Playlist

	var sublimeWidthObj="#playlist1";

`sublimeWidthObj` should be set as a jQuery-like selector of the object you'd like the video to resize itself to have the width of.

> Examples:

> If the ID of the object is 'wrapper', `var sublimeWidthObj="#wrapper"`

> If the class of the object is 'wrapper', `var sublimeWidthObj=".wrapper"`

If everything is properly set, your video should beautifully resize responsively.

## Contribute

Feel free to contribute. https://github.com/jonsuh/SublimeVideo-jQuery-Responsive-Resize

## License

Licensed under the [MIT](http://opensource.org/licenses/mit-license.php). http://opensource.org/licenses/mit-license.php

Copyright (c) 2012 [Jonathan Suh](mailto:hello@jonsuh.com) | [@jonsuh](https://twitter.com/jonsuh)

http://jonsuh.com