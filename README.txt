Skin Detaction using RGB, YCbCr and HSV

Source Code (folder name)

In the "Source Code" folder there is one file named "skin_detaction.ipynb".
To execute the file you can use either Jupiter notebook or Google Colab.
The preferred platform is Google Colab because there is one patch fixing library (from google.colab.patches import cv2_imshow) which is available in Colab and that is used in the source file. 
You can execute this file in Jypyter Notebook by replacing "cv2_imshow" with "cv.imshow" in the entire code and removing "from google.colab.patches import cv2_imshow".

Steps to execute source file in Google Colab
Step-1: Open "skin_detaction.ipynb" in Google Colab
Step-2: Upload all test images from "Given Test Images" and "Other Test Images" folders to the Colab editor. To upload click on the folder icon which is on the left side of the Colab editor. Then right-click just below to the "sample_data" folder and click on upload.
Step-3: Click on "Runtime" on the menu bar and click on "Run all"

Given Test Images:
This Folder contains all given test images and their results in the "Results" folder.

Other Test Images:
This Folder contains all given test and ground truth images and their results in the "Results" folder.