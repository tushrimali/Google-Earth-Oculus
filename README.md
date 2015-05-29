# Google-Earth-Oculus
Experience the stunning features of Google Earth in an Oculus DK2. Built using the WebVR AP &amp; Google Earth API


Notes: 

Setup:
	•	Works best with 32-bit Firefox Nightly and/or Chromium dev builds since these two browsers support google earth plug-ins
	•	Fire up 199.html
	•	Use WASD to move forward backwards and strafe left and right
	•	Use arrow keys to change camera angle
	•	If using without Oculus, you can either use just the Desktop screen or an Oculus emulator. Download Oculus Overlay (emulator) from here: http://holophone3d.com/oculus/


TO DO:
	•	If using an Oculus, the WebVR scripts might need to updated since the WebVR API is experimental and changes on a weekly basis
	•	Currently, the build supports DK2 but head tracking is very difficult due to to the super-slow plugin latency. The best option is to use in built navigational controls and view the output on Oculus

Code Sources:
 
From Google Earth API playground (Apache 2.0 license):
Keyboard hack and math3d: http://earth-api-samples.googlecode.com/svn/trunk/demos/stereo/stereo.html
Stereoscopic Vision: http://earth-api-samples.googlecode.com/svn/trunk/demos/firstpersoncam/index.html

WebVR Open Source API:
WebVR: http://mozvr.com/
