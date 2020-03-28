# Road-Lane-Detection-Using-OpenCV-and-Hough-Lines-Transform
Road Lanes are detected using Hough Transforms
Hough Transform : Detect Geometrical shapes if the shapes can be represented in the mathematical form. First apply Canny edge detection to the image - we need geometrical representation of the edges- hough transform can be used to find the geometrical representation of edges- hough transform is the mechanism which gives more emphasis to the edges pixels which are already in the geometrical shape (line in this example)

Steps involved to implement Hough Transform
1. Canny edge detection
2. mapping edge points to hough space(as a line according to me) and storage in an accumalator
3. Interpretation of the accumalator to yeild infinite lines using thresholding
4. Converting infinite line as a finite line.
