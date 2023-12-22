# Object-Detection-MaskRCNN
Mask R-CNN is a deep learning framework for object detection and instance segmentation. It is a state-of-the-art method that has been shown to achieve excellent results on a variety of object detection benchmarks.

### Overview 
In this project, Mask R-CNN is used to detect a wide variety of objects, including cars, people, animals, and buildings in a video. It is particularly well-suited for detecting objects in complex scenes, such as street scenes which is the sample video taken in this project.

### MaskRCNN model architecture
Mask R-CNN works by first using a convolutional neural network (CNN) to extract features from an image. The CNN is then used to generate a set of region proposals, which are candidate bounding boxes for objects in the image. The region proposals are then passed to a fully connected network (FCN), which classifies each region proposal and predicts a mask for the object within the region proposal.

![2884d889-f0b0-44e5-83cf-22ec8797f59a](https://github.com/swethasubu93/Object-Detection-MaskRCNN/assets/109064336/d351af3f-c548-4d3b-a619-6be61970b8d7)

### Model Inference 
[Jupyter Notebook](https://github.com/swethasubu93/Object-Detection-MaskRCNN/blob/main/swetha_hw4_method1_MaskRCNN_RetinaNet.ipynb)

The MaskRCNN model was used to predict the objects on a street. For comparison, Faster RCNN and RetinaNet152 models were also used for inference. 
The code for both models are given, along with inference videos.
The inference by Mask RCNN was found to be the best followed by FasterRCNN. The inference by RetinaNet was not as precise.

##### Inference by MaskRCNN
https://github.com/swethasubu93/Object-Detection-MaskRCNN/assets/109064336/0e5ce5f5-1844-4a34-b2b3-b9459a793806

##### Inference by RetinaNet
https://github.com/swethasubu93/Object-Detection-MaskRCNN/assets/109064336/57ef5dc6-2810-4990-af5d-820f313a12e1



