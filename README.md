# Face-Mask-Detection
Face Mask Detector for COVID-19 Pandemic

# Algorithm used for object detection - YOLOv3
  YOLO (You Only Look Once) takes only one forward propagation pass through the network to make the predictions.
  YOLO V3 was implemented using a darknet framework, which originally has a 53 layer network trained on Imagenet. 
  For the task of detection, 53 more layers are added to it, giving us a 106 layer fully convolutional underlying architecture for YOLO V3
  The algorithm divides the image into grids and runs the image classification and localization algorithm on each of the grid cells. 
  It predicts N bounding boxes and confidence scores in each grid. The confidence score reflects the accuracy of the bounding box of that class.
  
# Google Colab -
   Colab allows anybody to write and execute arbitrary python code through the browser, and is especially well suited to machine learning, 
   data analysis and education. More technically, Colab is a hosted Jupyter notebook service that requires no setup to use, while providing 
   free access to computing resources including GPUs.

# Steps to execute the Project -
Step 1 : Prepare the dataset\n
Step 2 :  Set up google drive and collab accounts \n
Step 3 : Clone, Configure and compile Darknet
Step 4 : configure yolov3.cfg file 
Step 5 : create .names file
Step 6 : create .data files
Step 7 : create folder for image
Step 8 : Download pre-trained weights
Step 9 : start training
