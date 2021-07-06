# FingerTip_Sketch

Sketching in the Screen with OpenCV

In this the fingertip can be used for drawing on screen with any possible colors present using OpenCV.

To achieve the target, Color Detection and Tracking is used.

Steps involved are :

• The Color marker touched by the fingertip is detected and mask is produced.

• The further prcoess involves Morphological operations on the mask prdocued which are Erosion and Dilation.

• Erossion minimize the impurtities present in the mask.

• Dilation restores the eroded main mask.

# Algortihm : 


• Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)

• Prepare the canvas frame and put the respective ink buttons on it.

• Adjust the trackbar values for finding the mask of coloured marker.

• Preprocess the mask with Morphological Operations (Erotion and dilation). 

• Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .

• Finally draw the points stored in array on the frames and canvas .
