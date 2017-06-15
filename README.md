## MARSBox - Matt's Augmented Reality Sandbox

This project is the result of my third year university project, and is still being developed.  The code will be uploaded in the next few weeks once it has been improved 

The program is written in C++ and uses GLFW, the Kinect V2 API and several other small libraries.  The input depth data is captured using a Kinect V2 connected to the computer via a Windows adapter.  The height data is then converted to a colour value within the HSV colour space, and drawn to the GLFW window.  The Marching Squares algorithm is then applied to the data in order to calculate the contour lines, and once this has been completed they are also drawn to the window.  Different colour themes and effects can be applied, and I currently have a very basic implementation of fluid simulation implemented which I hope to develop into a working one.  I will most put the Marching Squares implementation up as another project since there doesn't seem to be many available.  Here are some pictures showing what I have so far.


![Image](Images/20170502_135532.jpg)
