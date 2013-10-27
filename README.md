# Kinect + Processing 2

## Basic Setup
- Install Processing 2 (v2.0.3 as of Oct. 26, 2013)
- Start Processing.app, it requires Java
  - If you don't have Java yet, follow the instructions to install it.

## Kinect Driver Setup
We'll use the [Simple-OpenNI wrapper](https://code.google.com/p/simple-openni/) for the OpenNI Kinect drivers. These are required to allow Processing to send commands to and receive data from the Kinect controller.

On OS X, there are two methods for installing the Simple-OpenNI library for Processing.

### (RECOMMENDED) Install method 1: Let Processing (v >= 2.0) do it for you
- With a sketch open go to `Sketch > Import Library... > Add Library...` in the top menu bar
![Import SimpleOpenNI](https://raw.github.com/mudphone/AnotherKinectStarterKit/master/IMAGES/INSTALL/InstallSimpleOpenNI.png)
- Search for `SimpleOpenNI` in the *Library Manager* window
![Import SimpleOpenNI](https://raw.github.com/mudphone/AnotherKinectStarterKit/master/IMAGES/INSTALL/SearchForSimpleOpenNI.png)
- Install *SimpleOpenNI by Max Rheiner*
- Find the SimpleOpenNI example sketches, by going to the `File > Examples...` menu item
![Import SimpleOpenNI](https://raw.github.com/mudphone/AnotherKinectStarterKit/master/IMAGES/INSTALL/OpenSimpleOpenNIExamples.png)
- Open one of the SimpleOpenNI examples, listed under `Contributed Libraries > SimpleOpenNI > OpenNI`. I recommend the *AlternativeViewpoint3d* sketch for starters.
![Import SimpleOpenNI](https://raw.github.com/mudphone/AnotherKinectStarterKit/master/IMAGES/INSTALL/SimpleOpenNIExamplesList.png)

### Install method 2: Download and do it yourself
- [Download the Simple-OpenNI library.](https://code.google.com/p/simple-openni/downloads/list)
- Install the [Simple-OpenNI library](https://code.google.com/p/simple-openni/wiki/Installation) (for OS X, you don't do anything for this step)
- Open the zip file, and move the *SimpleOpenNI* folder to your Processing installation's *libraries* folder. This is usually located here: `~/Documents/Processing/libraries`
- Look in the `SimpleOpenNI/examples/OpenNI` folder and run some of the example sketches
