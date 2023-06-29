STEP 1: The only library we need for converting an image into a pencil sketch with Python is an OpenCV library in Python. It can be used by using the pip command; pip install opencv-python.  Let’s import it to get started with the task

STEP 2:cv2.imshow(“Title You want to give”, Image) and then simply write cv2.waitKey(0). This will display the image.

STEP 3: Now the next thing to do is to read the image.

STEP 4:Now after reading the image, we will create a new image by converting the original image to greyscale.

STEP 5:Now after reading the image, we will create a new image by converting the original image to greyscale .next step in the process is to blur the image by using the Gaussian Function in OpenCV.

STEP 6:Then the final step is to invert the blurred image, then we can easily convert the image into a pencil sketch.

And finally, if you want to have a look at both the original image and the pencil sketch.
So this is how we can convert an image into a pencil sketch with Python.
