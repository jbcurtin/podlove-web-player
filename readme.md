# Podlove Web Player

## About

HTML5 Goodness for Podcasting

Podlove Web Player is a Podcast-optimized, HTML5-based video and audio player with Flash fallback.
It can be used as a WordPress plugin or within a static HTML/JavaScript context.

The Podlove Web Player supports almost every modern browser and also does captions, chapters and much more.
Thanks to MediaElement.js for providing the foundation.

* [Official Site on podlove.org](http://podlove.org/podlove-web-player/)
* [WordPress Plugin Page](http://wordpress.org/plugins/podlove-web-player/)

## Build

We will replace *make* with *grunt.js* or *gulp.js* in combination with *browserify*.

Install prerequisites for building:

    npm install -g browserify

Create podlove-web-player/static/podlove-web-player.js with

    browserify main.js -o static/podlove-web-player.js

## Test

No automated tests, yet. Sorry.
But with `http-server` npm module you can serve the repository root directory statically for manual local frontend testing.
You can then access the examples with your browser via `http://localhost:8080/example/index.html`.

## Info

**Important!**
The Wordpress-plugin that includes the Podlove-Webplayer alone will be moved to its own repo.


Contributors:
[Gerrit van Aaken](https://github.com/gerritvanaaken/), [Simon Waldherr](https://github.com/simonwaldherr/),
[Frank Hase](https://github.com/Kambfhase/), [Eric Teubert](https://github.com/eteubert/),
[Juri Leino](https://github.com/line-o) and [others](https://github.com/podlove/podlove-web-player/contributors)
Version: 2.1.0-alpha
License: [BSD 2-Clause License](http://opensource.org/licenses/BSD-2-Clause)
