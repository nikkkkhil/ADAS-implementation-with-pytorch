# lane_detection- image & video

This method use opencv to detect lanes</br>

The concrete procedures are as follows:
1. Convert the image to gray level
2. Gaussblur to remove the noise
3. Use Canny method to trace out the lines
4. Use Hough Transform to find the lines
......

The result of this method is:
![Image text](https://github.com/mjDelta/CV-in-ADAS-pytorch/blob/xiao/tradition_lane_segmentation/result_img/result.png)
