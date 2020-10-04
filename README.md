# Accessing-Images

### Libraries
         import numpy      
         import cv2

         img=cv2.imread('E-learning.jpg')   

cv2.imread() function is used to read a jpg/png types of images from your file folders.

         cv2.imshow('image',img)            

cv2.imshow() function is used to present the selected image in the terminal.

         cv2.waitKey(0)                     

v2.waitKey() is used to wait for the user input for a time period of millisec.If the user presses a key the it returns a ASCII value.

         cv2.destroyAllWindows()           

cv2.destroyAllWindows() is used to shut down all windows of the terminal after the user exits.
