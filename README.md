# 3-Histograms-Equalization
Histogram equalization is an image processing technique that enhances an image’s contrast by redistributing its pixel intensity values across the entire range. This improves visibility, particularly in images with low contrast, by spreading out the most frequent intensity levels, making details in both dark and bright areas more distinguishable.
Histogram Equalization increases the global contrast of an image, particularly useful when the image's pixel intensity values are clustered closely together.
The process improves the visibility of details in regions with low local contrast.
OpenCV provides the cv2.equalizeHist() function to perform histogram equalization.
