# Hand-Detection-AR

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
