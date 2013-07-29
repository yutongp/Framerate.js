Framerate.js
============

Monitor web application frame rate

tested on:

* Chrome v28.0.15
* Safari 6.05
* Firefox 22.0

###Usage

	//New
	framerateObj = new Framerate();
	
	//Start
	framerateObj.start();
	
	//Read Avg Framerate
	var avgFramerate = framerateObj.updateAvgFramerate();
	
	//Reset
	framerateObj.reset();
