# Deblurring
Deblur an image using the Wiener filter in OpenCV
import cv2
import numpy as np

image = cv2.imread('blurred_image.jpg')
psf = np.ones((5, 5), np.float32) / 25  # Point spread function (PSF)

# Implement image deblurring using the Wiener filter

cv2.imwrite('deblurred_image.jpg
