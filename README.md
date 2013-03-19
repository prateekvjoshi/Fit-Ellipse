Fit-Ellipse
===========

Find contours in the given image and approximate it by ellipses. This technique is very useful in building models for object recognition. This code implements OpenCV based ellipse fitting. I have included a couple of sample input images along with this project. There is a file called "CMakeLists.txt". This file will be used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main image1.jpg 

When you run the code, a window will pop up with a slider bar. Move it around to set different thresholds. 