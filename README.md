This program calculates the MTF50 (Modulation Transfer Function 50%) of an image, which is a key metric for evaluating optical image quality. The program includes the following steps:

Image Loading: It loads a color image using OpenCV.

Image Cropping: A specific region of the image is cropped and converted to grayscale for further processing.

Region Localization: It detects edges, identifies contours, and determines the Region of Interest (ROI) for MTF calculations.

MTF50 Calculation: It calculates the MTF curve and extracts the MTF50 value (50% modulation) for specific ROIs.

Visualization: The results, including the MTF curves and MTF50 values, are plotted using Matplotlib for better analysis and interpretation.
