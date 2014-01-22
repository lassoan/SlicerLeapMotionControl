= One-time setup =

* Download and install Leap driver from https://www.leapmotion.com/setup
* If using other than 3D Slicer Win64 release, download the LeapMotion SDK from https://developer.leapmotion.com/ and copy all the lib files into this directory (where this readme.txt is located)
* Start 3D Slicer
* Add this directory to the module paths: Edit/Application settings, Modules, Additional module paths, >>, Add
* Restart Slicer

= Usage examples =

* Open TwoFingerSliceBrowsing.mrb scene
* Browse slices by moving two fingers in the Leap's field of view

* Open AllFingerFiducials.mrb scene
* Position the 5 markups by moving up to 5 fingers in the Leap's field of view

* Open the Gesture control / LeapMotion control module
* Click Auto-create transforms
* Move hand(s) and finger(s) in the Leap's field of view, transforms will be created automatically (name: HandXFingerY)
