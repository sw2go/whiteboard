# whiteboard

play with it:
https://sw2go.github.io/whiteboard/index.html
https://sw2go.github.io/whiteboard/v8.html



V8 Prompt:

Create HTML/JS sample code for SVG based whiteboard.

Ensure the code is really working 100% .

Environment details:
- Pure pure HTML/JS only
- Run in any modern browser (Chrome, Edge, Safari) on PC, Tablet and Mobile (Android and I-Phone)?

Exact feature list:
- open SVG
- save SVG
- save PNG (with transparent background)
- color picker
- stroke with slider
- erase mode, to remove specific line 
- multi-touch
- pan/zoom and consider all required screen/viewbox conversion 

Behavior expectations:

- SVG file should open standalone in a browser after download
- PNG export should have transparent background
- Board resize dynamically with the window
- after panning or zooming, adjust drawing coordinates
- when in erase mode display this with color on r

Performance constraints:
- It is okay to use inline JavaScript only. 
- Do not split into separate .js and .css files.

Testing target:
- Desktop 
- Mobile (iPhone and Android)
- Single-touch gestures (drawing with one finger only)

V10 Prompt:

Create HTML/JS single file sample code for SVG based whiteboard.

Ensure the code is working 100% and fullfilling all below requirements.

Environment details:
- Pure HTML/JS only
- Run in any modern browser (Chrome, Edge, Safari) on PC, Tablet and Mobile (Android and I-Phone)

Exact feature list:
- open SVG
- save SVG
- save PNG (with transparent background)
- color picker
- stroke witdh slider
- display erase mode
- multi-touch
- pan/zoom and consider screen/viewbox conversions 
- move function, to move board center (infinit board)

Behavior expectations:
- SVG file openable standalone in a browser after download
- PNG export with transparent background
- Board resize dynamically with the window

Testing target:
- Desktop 
- Mobile (iPhone and Android)
- Single-touch gestures (drawing with one finger only)


V11 Prompt:

Create HTML/JS single file sample code for SVG based whiteboard.

Ensure the code is working 100% and fullfilling all below requirements.

Environment details:
- Pure HTML/JS only
- Run in any modern browser (Chrome, Edge, Safari) on PC, Tablet and Mobile (Android and I-Phone)

Exact feature list:
- open SVG
- save SVG
- color picker
- stroke witdh slider
- mode options: draw, pan, erase
- multi-touch
- on mobile zoom with 2 fingers, on pc zoom with mouse wheel, zoom at current mouse or finger location  
- pan to have infinit board
- erase when touching or crossing a line
- consider screen/viewbox conversions on pan and zoom

Behavior expectations:
- SVG file openable standalone in a browser after download
- Board resize dynamically with the window

Testing target:
- Desktop 
- Mobile (iPhone and Android)
- Single-touch gestures (drawing with one finger only)
