# FingerTip_Sketch

Sketching in the Screen with OpenCV

In this the fingertip can be used for drawing on screen with any possible colors present using OpenCV.

To achieve the target, Color Detection and Tracking is used.

Steps involved are :

• The Color marker touched by the fingertip is detected and mask is produced.

• The further prcoess involves Morphological operations on the mask prdocued which are Erosion and Dilation.

• Erossion minimize the impurtities present in the mask.

• Dilation restores the eroded main mask.

