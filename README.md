# underwater-image-processing

This repository contains a Python script that utilizes OpenCV for image processing tasks, including resizing images and displaying them in a Google Colab environment.

Table of Contents
Installation
Usage
Functions
License
Installation
To run this code, you need to have the following libraries installed:

OpenCV
NumPy
Google Colab (for displaying images)
You can install the required libraries using pip:

bash
Copy
pip install opencv-python numpy
Usage
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/repository-name.git
cd repository-name
Open the Jupyter Notebook in Google Colab (if applicable) or run the script in your local environment.

Import the required libraries:

python
Copy
import cv2
import numpy as np
from google.colab.patches import cv2_imshow
Load an image and call the resize_image function to resize it as needed.

Display images using cv2_imshow.

Functions
resize_image(image, width=None, height=None)
Resizes the input image to the specified width and height.

Parameters:

image: The input image to be resized.
width: Desired width of the output image (optional).
height: Desired height of the output image (optional).
Returns: The resized image.

Example Usage
python
Copy
image = cv2.imread('path_to_your_image.jpg')
resized_image = resize_image(image, width=300)
cv2_imshow(resized_image)
License
This project is licensed under the MIT License - see the LICENSE file for details.

