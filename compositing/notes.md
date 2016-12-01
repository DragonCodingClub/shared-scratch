
Interested in puzzle game with a reveal.  Saw an interesting game with paint splashes. 

Trying a turn based reveal an image.

Found

http://stackoverflow.com/questions/18379818/canvas-image-masking-overlapping


Created locally and tried to just draw one image statically with the mask.



Found the fillRect code and got to w3schools from a google search: 

http://www.w3schools.com/TAgs/canvas_fillrect.asp


Played a lot commenting out in sequence to see effects

Found “canvas tainted” http://stackoverflow.com/questions/16217521/i-get-a-canvas-has-been-tainted-error-in-chrome-but-not-in-ff

and --allow-file-access-from-files


found I had got offtrack with getting the current image from the canvas, it works just to keep redrawing the image. 


It worked, so switched into the mouse up handler. 

looked up calculating positions