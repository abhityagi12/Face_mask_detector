# Face_mask_detect

This is a working project to detect people wearing masks in real time. I have used pre-trained Face detector based on SSD framework (Single Shot MultiBox Detector), using a reduced ResNet-10 model. (refer this: https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/)
Once the faces are detected, then a fine-tuned MobileNetV2 is used as a classifier to detect masks.

Implementation:
1. If you want to use this trained model-- Simply download this repo and run the file real_time_mask_detect.py

2. If you want to train your own model, then copy images in the dataset folders (explained in about.txt files).
   run the file train.py, giving your own arguments as required to save the model.
   after training, run real_time_mask_detect.py.
   
Thanks!
