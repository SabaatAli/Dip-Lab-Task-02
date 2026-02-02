\\DIP Task 02 – Basic Digital Image Processing Operations

Overview
This project implements fundamental digital image processing operations using Python. The program processes a color image to explore color components, grayscale conversion, binary thresholding, and object detection through connected component analysis.

Objectives
To load and display a color image
To extract and visualize RGB color components
To convert a color image into grayscale
To generate a binary image using thresholding
To detect and count objects using connected component analysis
To visualize labeled objects with distinct colors

Tools & Libraries Used
Python
OpenCV (cv2)
NumPy
Matplotlib

Processing Steps
1. Image Loading
The input image is loaded in RGB format and displayed for reference.

2. RGB Channel Extraction
The Red, Green, and Blue components are extracted and displayed separately to observe their individual contributions.

3. Grayscale Conversion
The color image is converted into a grayscale image to simplify further processing.

4. Binary Thresholding
A binary image is created by applying thresholding on the grayscale image, separating foreground objects from the background.

5. Connected Component Analysis
Connected component labeling is performed on the binary image to:
Detect individual objects
Count the total number of objects
Assign a unique label to each object
Each detected object is displayed using a randomly assigned color for easy visualization.

Results Visualization
The following outputs are displayed using Matplotlib:
Original RGB image
Individual R, G, and B channel images
Grayscale image
Binary thresholded image
Connected component labeled image

Applications
Object detection and counting
Image segmentation
Computer vision preprocessing
Educational digital image processing experiments

Conclusion
This task demonstrates the core building blocks of digital image processing. By combining color analysis, thresholding, and connected component labeling, meaningful information can be extracted from images in a simple and effective manner.