[![N|Solid](https://media.geeksforgeeks.org/wp-content/uploads/20191130172155/results_screenshot_30.11.2019.png)](https://media.geeksforgeeks.org/wp-content/uploads/20191130172155/results_screenshot_30.11.2019.png)
# Road Lane line detection using Python !
[~ By Mayuresh Patil]()

Using computer vision techniques in Python, we will identify road lane lines in which autonomous cars must run. This will be a critical part of autonomous cars, as the self-driving cars should not cross it’s lane and should not go in opposite lane to avoid accidents.

## Frame Masking and Hough Line Transformation
To detect white markings in the lane, first, we need to mask the rest part of the frame. We do this using frame masking. The frame is nothing but a NumPy array of image pixel values. To mask the unnecessary pixel of the frame, we simply update those pixel values to 0 in the NumPy array.

After making we need to detect lane lines. The technique used to detect mathematical shapes like this is called Hough Transform. Hough transformation can detect shapes like rectangles, circles, triangles, and lines.

## Dependencies
```
pip install matplotlib
```
