# Hand-Detection-AR

Following are the steps to setup and run the android project
1)	git clone https://github.com/mubeenahmed/Hand-Detection-AR hand-detection
2)	Download opencv for android from http://opencv.org/downloads.html
3)	Open the project in Android Studio
4)	Go to File > New > Import Module
5)	Browse the path to opencv for android library
6)	Click finish


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
