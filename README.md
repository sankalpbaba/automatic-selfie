# automatic-selfie

It is a very basic program for computer vision application.
The dataset files are haarcascade_frontalface_default, haarcascade_smile 

**Haar Cascade**
Haar Cascade is an ML object detection algorithm used to identify objects in an image (treated as a matrix i.e. 2D grid here) or video.
In this algorithm, a cascade function is trained from a lot of positive and negative images which is then used to detect objects in other images. It can be trained to identify almost any object. In this project, we will be using these pre-trained files.

**The algorithm has four steps:**

* Haar Feature Selection
* Creating  Integral Images
* Adaboost Training/selfieboost
* Cascading Classifiers

The webcam will start once you run it and it will save the image file as we smile and 'smile' feature is determined by haar cascade file we uploaded for smile.The adaboost training is used as adaboost in Face detection requires a binary classifier (face versus non-face). Adaboost does have multi-class variants but we stick to the 2-class case. error-rate less than 50%, i.e. they must be at least slightly better than random guessing. If the rule of thumb has more than 50% error, just invert its sign!
Press q to quit or stop the application.
