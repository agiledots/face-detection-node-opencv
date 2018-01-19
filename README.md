# face-detection-node-opencv

Real-time face detection using OpenCV, Node.js, and WebSockets.

Click [here](http://youtu.be/v2SY0naPBFw) to see it in action.

## Requirements

* [Node.js](http://nodejs.org/)
* [OpenCV 3.4.0](http://opencv.org/)
    * May also work with older versions of OpenCV, but most recently tested with OpenCV 3.4.0
* A webcam, e.g. laptop-integrated webcam, USB webcam

## Installing Node.js packages

* Download OpenCV from [here](https://opencv.org/opencv-3-4.html)
* Extract it to your C: drive, And set environment variables `OPENCV_DIR = C:\OpenCV\build\x64\vc15 `

* Navigate to the `server` directory
* To install the packages: `npm install`

## Running the demo

* Make sure you are still in the `server` directory
* To run the server: `node server.js`
* To run the demo locally, open a browser and go to `localhost:9000`

The app should be up and running!
