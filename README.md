# p0weruser
Extend pr0gramm.com with some extra functions and improve look and feel. Don't like a special feature? No problem, just disable
it using settings.

## Features
* Addon-Settings
* Repost-Highlight
* Widescreen mode
* Current benis in header
* Notification Center
* Advanced Comments
* (planed) Integration of Rene8888s repost-check
* (planed) Highlighting of previously visited posts
* (planed) A poor man's "stelz"
* (planed) Slideshow mode
* (planed) Improved search

## Installation
Just install Greasemonkey or Tapermonkey and install the script by a simple
click on one of the following urls:
### Release [![Build Status](https://travis-ci.org/FlorianMaak/p0weruser.svg?branch=master)](https://travis-ci.org/FlorianMaak/p0weruser)
[https://github.com/FlorianMaak/p0weruser/raw/master/dist/p0weruser.user.js](https://github.com/FlorianMaak/p0weruser/raw/master/dist/p0weruser.user.js)

### Beta [![Build Status](https://travis-ci.org/FlorianMaak/p0weruser.svg?branch=develop)](https://travis-ci.org/FlorianMaak/p0weruser)
[https://github.com/FlorianMaak/p0weruser/raw/develop/dist/p0weruser.user.js](https://github.com/FlorianMaak/p0weruser/raw/develop/dist/p0weruser.user.js)

## Contribution
Feel free to fork this project. If you like to contribute, please use git-flow
branch-style and follow the commits conventions. If your work is done, please submit a
pull request. All contributions will be released under GPLv3 licence.

## [Dev] Installation
After checkout run ```npm install``` and npm will install all needed dependencies
and will run ```bower install``` to install needed frontend-libaries. After installation run
```npm run build``` to build a bundle from source. There are filewatchers running, starting a new build after a
each filechange. Just create a new UserScript in Tapermonkey and add your local file (found in
```dist``` folder) to test your script. 
