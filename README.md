# Image analysis and pattern recognition Project

 # preprocessing
 #1. Show the histogram of the image "Crayfish_NG.jpg". Analyze the histogram obtained: identify the problem and explain the different solutions possible.
 #2. test several preprocessing operations:

      a. Histogram Stretching (Dynamic Range Adjustment) of the image "Crayfish_NG.jpg".
      b.Histogram Equalization of the image "Crayfish_NG.jpg".
      c.perform 2D convolution of the image "Crayfish_NG.jpg" with these 2 following filters:
          filter_1 = ([[1, 2, 1],
                     [2, 4, 2],
                     [1, 2, 1]]) / 16

          filter_2 =([[-1, 0, 1],
                     [-2, 0, 2],
                     [-1, 0, 1]])
      d. remove noise from the "brain.png" image.
 #3.We want to test the effect of several morphological operations. Apply to image "J.png" of the following operations: erosion, dilation, opening and closing.
 
 # Object Extraction
 #1. extract the object from the image "Texte_NG.jpg" by the types of most suitable methods for performing segmentation.
 #2. First, we'll test a segmentation method based on unsupervised classification (the k-means method)
 #3. Next, we look at thresholding-based segmentation methods:
    a. Apply the global thresholding method. Identify the appropriate threshold directly from the histogram.
    b. Apply the OTSU global thresholding method.
    c. Apply an adaptive thresholding method. Comment on the results obtained.

 # object extraction using a region-based approach, followed by a contour-based approach.
  #1. Test the “feuille.png” region growth method.
  #2. Consider the following filters:
     filter_1 = ([[1, 0, -1],
                     [2, 0, -2],
                     [1, 2, -1]]) 

     filter_2 =([[1, 2, 1],
                     [0, 0, 0],
                     [-1, -2, -1]])

  a- Specify the role and type of each of the filters (1) and (2).
  b- Detect the outline of the object in the “feuille.png” image using both filters (1) and (2). 
  c- Using filters (1) and (2), find two additional filters that detect diagonal contours,and Apply them to detect the outlines of the object   in the image "feuille.png".
 #3. Apply the Canny filter to extract the object of interest from the “feuille.png” image.
 #4. Apply the active contour method to the “feuille.png” image.
 #5. Apply the Hough transform to the “road.png” image to detect straight lines in this image.