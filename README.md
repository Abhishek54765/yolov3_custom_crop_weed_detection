# yolov3_custom_crop_weed_detection
In this I have implemented object detection by using state_of_the_art algorithm that is yolov3. I have trained my yolov3 model on 1300 weeds and crop images. With 6 hours of training on google colab Tesla T4 gpu i was able to get prety good results.

link for dataset = https://www.kaggle.com/ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes

This is the link for the weights that i got after traing the model for 6 hours on google collab gpu Tesla-T4. You can download and test it out. - https://drive.google.com/file/d/1YqxVo4FutSs7ogUob8YS_b2_QYLWbp3M/view?usp=sharing

Description of files - 
yolov3.cfg is the configuration file for testing the data in this i have set the batch size and subdivisions to 1. If anyone wants to use this file for training the the model then one can change the batch size to 64(desired) and subdivision according to ones need.
