To describe a specific position on the surface of the Earth, we must rely on the
[geographic coordinate system](http://en.wikipedia.org/wiki/Geographic_coordinate_system).
The geographic coordinate system is a method used to give every possible location on Earth to be
specified by a set of numbers or letters. A common choice of coordinates is 
[latitude](http://en.wikipedia.org/wiki/Geographic_coordinate_system) 
and [longitude](http://en.wikipedia.org/wiki/Longitude).
With this information we can calculate a distance between two points along a surface.

For simplicity’s sake, we will suppose that the Earth is a perfect sphere with a radius of 6,371
kilometers (it gives a mistake no more than 0.3%).
You are given two point coordinates and you must find the shortest distance between
these points on the surface of the Earth, measured along the surface of the Earth.

Coordinates are given as a string with the latitude and longitude separated by comma and/or whitespace.
Latitude and longitude are represented in the follow format: ```d°m′s″X```

In this example, "d" is degrees, "m" is minutes, "s" is seconds as integers, while "X" is "N"
(north) or "S" (south) for a latitude and "W" (west) or "E" (east) for a longitude.

The result should be given as a number in kilometers with a precision of ±0.1 (100 metres).
