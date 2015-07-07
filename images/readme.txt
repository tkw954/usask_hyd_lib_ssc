Note on creating images for block diagrams
-Create in Visio, using "Fluid Power" Template
-Add component to diagram
-Change line width as appropriate
-Add a white rectangle with no line behind the component to adjust its position
-Export as png with default settings

To add to block
-in mask editor, "Icon & Ports" tab, add command, e.g. "image('simpleThreeWayValve.png')"
-add ports, e.g. color('red');port_label('lconn',1,'x');
-set "block frame" to "invisible", "icon rotation" to "rotates" and "port location" to "physical"

-Note that if you change the png file, Matlab will not load the new file without restarting Matlab.
