# Image-Enhancement-Techniques-using-CV
Programs to apply 2D transformations such as Negative, Logarithmic,
Gamma, Affine, and Cropping on images to simulate real-world applications like
enhancing low-light photos, correcting geometric distortions, and extracting regions
of interest in satellite imagery.

# Libraries Used
1. OpenCV: Open Source Computer Vision Library, commonly used for image
processing tasks.
2. NumPy: A fundamental package for scientific computing in Python.
3. Matplotlib: A plotting library for creating static, animated, and interactive
visualizations.

# Functions and What We have Done
1. Reading and Verifying the Image:
  a. Read the image using cv2.imread and verified its successful loading.
  b. Extracted the dimensions of the image using image.shape.
2. Cropping the Image:
  a. Defined the coordinates and dimensions for the crop.
  b. Extracted a specific portion of the image using array slicing.
3. Affine Transformation:
  a. Defined source (pts1) and destination (pts2) points for the
  transformation.
  b. Computed the transformation matrix using cv2.getAffineTransform.
  c. Applied the affine transformation to the image using cv2.warpAffine.
4. Brightness Adjustment (Logarithmic Transformation):
  a. Converted the image to grayscale using cv2.cvtColor.
  b. Applied a logarithmic transformation to enhance the brightness.
5. Gamma Correction:
  a. Defined a gamma value.
  b. Applied gamma correction to adjust the image&#39;s brightness and
  contrast.
6. Negative Transformation:
  a. Applied a negative transformation to invert the image&#39;s pixel values.
