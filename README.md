Framerate.js
============

Monitor web application frame rate

tested on:

* Chrome v28.0.15
* Safari 6.05
* Firefox 22.0

###Usage

	//Start
	framerateObj = new Framerate();
	framerateObj.start();
	
	//read Avg Framerate
	var avgFramerate = framerateObj.updateAvgFramerate();
	
	//Reset
	framerateObj.reset();
