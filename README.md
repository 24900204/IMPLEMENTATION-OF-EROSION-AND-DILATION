# Implementation-of-Erosion-and-Dilation
## Aim
To implement Erosion and Dilation using Python and OpenCV.
## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step1:
Import the required libraries such as OpenCV, NumPy, and Matplotlib. Read the input image and convert it from BGR to RGB format for display.


### Step2:
Convert the input image into grayscale using cv2.cvtColor() to simplify processing.
### Step3:
Apply thresholding and edge detection (Canny Edge Detector) to identify edges in the image. Use Gaussian Blur to reduce noise.

### Step4:
Apply Hough Line Transform (cv2.HoughLinesP) to detect straight lines (lane lines) from the edge-detected image.

### Step5:
Compute slopes and intercepts of detected lines, extrapolate lane lines, and draw them on the original image. Finally, display the output using Matplotlib.

 
## Program:

``` Python
# Import the necessary packages



# Create the Text using cv2.putText



# Create the structuring element



# Erode the image




# Dilate the image





```
## Output:

### Display the input Image
<br>
<br>
<br>
<br>
<br>
<br>

### Display the Eroded Image
<br>
<br>
<br>
<br>
<br>
<br>

### Display the Dilated Image
<br>
<br>
<br>
<br>
<br>
<br>

## Result
Thus the generated text image is eroded and dilated using python and OpenCV.
