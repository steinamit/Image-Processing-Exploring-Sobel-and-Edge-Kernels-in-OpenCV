# Edge Detection with Sobel Kernels (Course Exercise)

Applies Sobel kernels to a photo to show how convolution finds horizontal and vertical edges.

**Context:** computer vision course exercise, built on a provided notebook.

## Steps
- Convert the image to grayscale.
- Apply a Sobel-y kernel with `cv2.filter2D` and a Sobel-x filter with `cv2.Sobel`.
- Compare the edge maps.

**Tools:** Python · OpenCV · NumPy · matplotlib
