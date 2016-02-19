#Spacebrew: Getting started
This is a simple repository with a few basic [Spacebrew](http://docs.spacebrew.cc) libraries, and the Spacebrew server.

##Setting up: Overall
* In the command line, ```cd``` to somewhere you'd like to put this
* Run this line to checkout the repository and initialize all submodules:

```
git clone https://github.com/robotconscience/spacebrew-getting-started.git && cd spacebrew-getting-started && git submodule update --init --recursive
```

* If you have [Node.js](https://nodejs.org/en/) installed, you may also run this line to setup the spacebrew server (assuming you're already inside the folder 'spacebrew-getting-started':

```
cd spacebrew && npm install ws && npm install forever-monitor
```

##Setting up: Libraries
* To use the Processing and openFrameworks libraries, you must move them into their proper homes:
	* Move spacebrewP5/dist/spacebrew into your Processing "libraries" folder (on OS X, that's usually ~/Documents/Processing/libraries).
	* Move ofxSpacebrew and ofxLibwebsockets into openFrameworks/addons