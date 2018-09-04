# OpticalFlowAnalysisForPedestrianCount
Count the number of people in video stream


# Execution of file: main.py
> python main.py 1.mov

> python main.py 2.mov


# Optical Flow
Optical flow is the pattern of apparent motion of image objects between two consecutive frames caused by the movemement of object or camera. https://docs.opencv.org/3.4/d7/d8b/tutorial_py_lucas_kanade.html


# Morphological Processing
Morphological transformations are some simple operations based on the image shape. It is normally performed on binary images. It needs two inputs, one is our original image, second one is called structuring element or kernel which decides the nature of operation. Two basic morphological operators are Erosion and Dilation. https://docs.opencv.org/trunk/d9/d61/tutorial_py_morphological_ops.html



# procedure
1. Calculate the optical flow vector for image pixels
2. Convert the image into binary image 
3. Remove noise by using morphological processing
4. Find contours and draw boundries
5. Count no of contours
