# Canny_edge_detection

## Canny Edge Detector For Simple Hand Posture Detection
 
### Step 1: Input Images:
1. The dataset consists of more than one image; each image has a different hand sign.
2. The user takes a picture of the hand to be tested either through the real-time orloaded image.

### Step 2: Image Pre-processing
1. The image is converted into grayscale
2. Enhancement image using Filters technique (Smoothing filter, sharping filter, smooth then sharp, sharp then smoothed, other)
3. Convert the grayscale image into a binary image.

### Step 3: Segmentation image from the background (how?)

### Step 4: Detect the border of the hand image
1. Apply the following filter (Sobel, Prewitt, and canny), and which one is better?
2. How did canny thin the edge?
3. How canny edgy detectors remove unimportant edges or weak edges.

### Step 5: display one image containing the original image, the gray image, and the edge image.

## Result

![Result](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/result.PNG?raw=true)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Project Requirements

## You, Will, create a Class with the following functions

• gaussianMask( parameters: Size of the mask, Sigma = 1) and return the mask
![gaussianMask](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/gaussian.png)

• convolute (parameters: image, filter) and return the result of convoluting the filter 

• sobel(parameters: image) and return the image containing the edge 
![sobel](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/sobil.png)

• Prewitt (parameters: image) and return the image edge 
![Prewitt](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/Prewitt.png)

• non-maxima suppression (parameter: Image, angels) and return the resulting image
![non-maxima suppression](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/non_maximaSuppression.png)

• double threshold(parameter: Image) and return result image 
![double threshold](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/double_threshold.png)

• Edge Linking(parameter: Image) and return result image contain the edge
![Edge Linking](https://github.com/Noureldin2303/Canny_edge_detection/blob/main/Images/EdgeLinking.png)

• Canny (parameters: image) and return the edge 

• Should contain lower and higher threshold values as data members to manipulate it and assume that filter size for all edge detectors is 3x3
