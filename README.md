# Image-Processing
Image processing application in Python. Tesing out Median filter and 8-bit Image Plane Slicing. 

### Files Uploaded
1. *Images* directory containing example images
2. *8-bit-slice.jpg* images to test program
3. Main *img_process.ipynb* notebook that contains the code

### 8-Bit Plane Slicing
Bit plane slicing highlights the contribution made to total image appearance by specific bits. Suppose that each pixel in an image is represented by 8 bits. Imagine that the image is composed of eight 1-bit planes, ranging from bit-plane 0 for the least significant bit to bitplane 7 for the most significant bit. Then extracting one of these planes from the 8-bit image is called Bit Plane Slicing.
![8-Bit Plane Slicing](/Images/bit_plane.jpg)

### Median Filter
Median Filter is an order-statistic filter that replaces the value of a pixel by the median of the gray levels in the neighborhood of that pixel (the original value of the pixel is included in the computation of the median). Median filters are particularly effective in the presence of both bipolar and unipolar impulse noise.

![Median Filter](/Images/median_filter.jpg)


