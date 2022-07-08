# Canny_edge_detection
 ##Canny Edge Detector For Simple Hand Posture Detection
 
##Step 1: Input Images:
A. The dataset consists of more than one image; each image has a different hand sign.
B. The user takes a picture of the hand to be tested either through the real-time orloaded image.

##Step 2: Image Pre-processing
A. The image is converted into grayscale
B. Enhancement image using Filters technique (Smoothing filter, sharping filter, smooth then sharp, sharp then smoothed, other)
C. Convert the grayscale image into a binary image.

##Step3: Segmentation image from the background (how?)

##Step 4: Detect the border of the hand image
a. Apply the following filter (Sobel, Prewitt, and canny), and which one is better?
b. How did canny thin the edge?
C. How canny edgy detectors remove unimportant edges or weak edges.

##Step 5: display one image containing the original image, the gray image, and the edge image.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Project Requirements
You, Will, create a Class with the following functions

• gaussianMask( parameters: Size of the mask, Sigma = 1) and return the mask
• convolute (parameters: image, filter) and return the result of convoluting the filter 
• sobil(parameters: image) and return the image containing the edge 
• Prewitt (parameters: image) and return the image edge 
• non-maxima suppression (parameter: Image, angels) and return the resulting image
• double threshold(parameter: Image) and return result image 
• Edge Linking(parameter: Image) and return result image contain the edge
• Canny (parameters: image) and return the edge 
• Should contain lower and higher threshold values as data members to manipulate it and assume that filter size for all edge detectors is 3x3
