# face-recogniser-sample
An OpenCV application for recognising eyes and face in video stream using pre-trained Classifiers.

## Methodology:
Here, Python 3.6 is used and OpenCV package had been used for training and detection.

Basically the steps followed are as follows:

- Initially the video frame from our webcam is read using OpenCV package.
- Then using the pre-trained classifiers, we detect the eyes and face through OpenCV functions and user defined functions.
- Then the images with rectangles around detected face and eyes are returned and displayed continuously in video format.

### Detection process:

- The image is initially converted to greyscale for easy computations.
- Then the haar-like features are checked using classifiers on this grey-scale image matrix.
- Those frames, which pass the threshold value are detected as faces and eyes.
- Then, these rectangles are drawn over the coloured image in the same location and displayed.
- We perform this process using user defined function and OpenCV package.
