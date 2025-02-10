### Digital Image Processing Lab Report

**Introduction**

This report provides an overview of the Digital Image Processing Lab, detailing the objectives, methodologies, and results of the exercises conducted. The focus is on implementing fundamental image processing techniques using Python and OpenCV.

**Faculty**

Audity Ghosh, Lecturer, Department of Computer Science & EngineeringUniversity of Information Technology and Sciences (UITS)


**Course Details**

Course Code: CSE 438

Course Title: Digital Image Processing Lab

Section: 8A (50th Batch)

Date: 5 February, 2025


**Objectives**

The primary objectives of this lab session are:

Understanding image processing operations in Python.

Extracting a specific region from an image.

Converting an image to HSV color space and analyzing its components.


**Lab Tasks**

*Task 1: Extracting a 100×100 Region from the Center of an Image*

Load an image from a given URL.

Determine the center coordinates of the image.

Extract a 100×100 pixel region from the center.

Display both the original and cropped image for comparison.

*Task 2: Converting an Image to HSV and Visualizing Components*

Convert the input image from RGB to HSV color space.

Extract and visualize the Hue, Saturation, and Value components individually in grayscale.

Analyze how HSV representation differs from RGB.


**Methodology**

Tools and Libraries Used

Python 3.x

OpenCV (cv2)

NumPy

Matplotlib


**Implementation**

Image Loading: Images are loaded from a URL using OpenCV.

Region Extraction: Using image slicing, a 100×100 pixel region is extracted from the center.

HSV Conversion: The cv2.cvtColor() function is used to transform RGB images into HSV format.

Visualization: The extracted components are displayed using Matplotlib.


**Results**

The extracted image region and HSV components are successfully visualized, demonstrating:

The ability to manipulate image regions programmatically.

How HSV color space represents image information differently than RGB.

How to Run (Google Colab)

Open Google Colab: Google Colab

Navigate to the repository:

%cd dip-lab

Open and execute the Jupyter Notebook:

!jupyter notebook santo_2125051047_8A.ipynb


**Conclusion**

This lab session successfully demonstrated basic image processing techniques in Python. The extraction of image regions and color space transformations provide fundamental insights into digital image processing.


**Future Work**

Extend the implementation to handle real-time image inputs.

Apply edge detection and filtering techniques.

Develop interactive tools for image manipulation.


**License**

This project is for educational purposes. Feel free to use and modify it as needed.

**Acknowledgments**

Special thanks to Audity Ghosh for guidance and support in this lab.
