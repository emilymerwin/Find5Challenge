#Find 5 Challenge
- Using excanvas for the canvas elements used to draw boxes around the answers for old versions of IE
- canvas.text.js also for handling text on canvas in IE?
- fader.js is for the sounds, I think?
- soundmanager2-nodebu-jsmin.js is for handling html5 compliant audio and falling back to flash audio if needed

###ToDo
- [ ] alignment of some labels and buttons is off on mobile
- [ ] Current audio format not supported by iOS
- [ ] Hide "Want to play more? Click here" on un-wrapped version served from iPad - maybe do this by detecting if it's in an iframe? <a href="http://stackoverflow.com/questions/326069/how-to-identify-if-a-webpage-is-being-loaded-inside-an-iframe-or-directly-into-t">link</a>

####Thoughts
- [ ] Would it be more efficient to create buttons or something from the hit areas and trigger the hit on click and miss when the background is clicked? Rather than check all 4 coordinates of each answer for every click...
- [ ] Using canvas to display the results text is a huge hassle - we needed canvas for drawing the boxes (or did we?) but why not just drop a new HTML div on top?

