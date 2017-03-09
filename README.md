# Hand-Detection-AR

Following are the steps to setup and run the android project
*	git clone https://github.com/mubeenahmed/Hand-Detection-AR hand-detection
*	Download opencv for android from http://opencv.org/downloads.html
*	Open the project in Android Studio
*	Go to File > New > Import Module
*	Browse the path to opencv for android library
*	Click finish


The methodology, as illustrated above, is:
* Take user input and detect hand color in HSV
* Segment hand and compute convex hull
* Use convex hull to detect fingertips
* Use distance transform to estimate palm center
* Render cube at palm center
* Set cube rotation speed with finger recognition
* Estimate depth with contour size and set cube scale


**Screenshot of final app in action:**

<img src="https://github.com/ad8454/Hand-Detection-AR/blob/master/ar_final.JPG" width="800">
