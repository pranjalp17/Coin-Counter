Coin Detection with OpenCV
This Python script detects coins in an input image using OpenCV. 
It applies image processing techniques like grayscale conversion, Gaussian blur, and Hough Circle Transform. 
After detecting coins, it outlines them on the original image and prints the number of coins detected along with their sizes (diameter).

Usage
Place the input image (c10.jpg in this example) in the same directory.
Run the script coin_detection.py.
The script will display the original image with detected coins outlined, print the number of coins detected, and their respective sizes (diameters).
Parameters
Adjust the parameters in the script to fine-tune detection:
dp,
minDist,
param1,
param2,
minRadius,
maxRadius,

Example
The provided ('c10.jpg') contains coins. After running the script, it displays the image with detected coins outlined, prints the count, and shows their sizes (diameters).
