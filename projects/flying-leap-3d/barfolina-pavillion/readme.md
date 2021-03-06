barfolina pavillion
===================

Live Demo: http://jaanga.github.io/gestification/projects/flying-leap-3d/barfolina-pavillion/r1/barfolina-pavillion.html

This demo app is intended to help users of [Leap Motion](http://leapmotion.com) devices learn how to fly through 3D space using their hands.

The app uses a modified version of the [Three.js](http://three.js) First Person Controller in order to provide a safer smoother flight experience.

The contents of the app provides a 3D representation of Mies van der Rohe's 1929 [Barcelona Pavillion](http://en.wikipedia.org/wiki/Barcelona_Pavilion).
The interesting aspect of this model is that it is generated by code instead of being data read from a file.


##Issues

###Content
Architecture: needs to be finished, including roofs, cross-shape columns, furniture, sculpture and so on
Landscape: better everything
Activity: people moving about, patterns of the water.

###Behavior
LeapMotion Interactions:
* Move forward/backard, left/right, up/down all need lookimg at and refining
* Pitch, roll and yaw: all need looking at and refining


##Roadmap / ideas
* use hand roll to speed up and slow down lookSpeed and movementSpeed

##Copyright and License
Copyright &copy; 2013 Jaanga authors

MIT License

##Change Log

2013-08-30 ~ Theo
* Added select controller menu and functions - helps with debugging
* Fixed placement of background 
* Added red css class to highlight freeze warning
* Sped up lookSpeed a bit
* Worked on various move parameters
* Added '+' shaped columns
* Added Georg Kolbe's 'Alba' sculpture - with temporary material
* Set windows to be a bit more opaque
* Various minor code clean-ups

2013-08-29 ~ Theo
* Folders and files added
* First Person Controller (FPC) can now 'clamp' the camers within a XYZ space
* FPC now has slightly better control over vertical movement

##Credits

'[Alba](http://sketchup.google.com/3dwarehouse/details?mid=842462e3fcec482c9ac3aefb8c574b8b)' (Dawn) a statue by Georg Kolbe
From Trimble 3D Warehouse
Uploaded by: Xray Haller on December 2, 2011
See: http://rumlig.blogspot.com/2011/11/barcelona-pavilion-statue.html



