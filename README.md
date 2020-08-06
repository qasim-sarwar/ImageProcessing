# Imagine we have an image. We’ll represent this image as a simple 2D array where every pixel is a 1 or a 0.
 	The image you get is known to have one or more rectangles of 0s on a background of 1s. 
 	Write a function that takes in the image and returns the coordinates of the rectangles --
 	either top-left and bottom-right; or top-left, width, and height.
  
  image = new int[,]
          {
          {1, 1, 1, 1, 1, 1, 1},
          {1, 1, 1, 1, 1, 1, 1},
          {1, 1, 1, 0, 0, 0, 1},
          {1, 0, 1, 0, 0, 0, 1},
          {1, 0, 1, 1, 1, 1, 1},
          {1, 0, 1, 0, 0, 1, 1},
          {1, 1, 1, 0, 0, 1, 1},
          {1, 1, 1, 1, 1, 1, 0},
          };
