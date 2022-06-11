# Lane-Detection
This repo contains code of lane detection application. I used Python and OpenCV to detect lane lines on the road.

# Architecture
1. Load test images
2. Apply Color Selection
3. Apply Canny edge detection
    - Apply gray scaling to the images
    - Apply Gaussian smoothing
    - Perform Canny edge detection
4. Determine the region of interest
5. Apply Hough transform
6. Average and extrapolating the lane lines
7. Apply on video streams

