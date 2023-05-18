# Image Segmentation of Indian Roads
Image Segmentation is one of the applications in Computer Vision. In this project, we will analyze a video recording of a vehicle driving on the road and we are going to classify each object in each frame and compute semantic segmentation for each frame in this video.

## Steps:-
- Extract frames and their corresponding frames from a zip file
- Train U-Net model architecture using ResNet34 as backbone for the model
- Implemented Dice Loss as loss function, Adam optimizer and improved IOU score while training model
- Tested U-Net model on new frames and was able to accurately segment objects in the test frames
- Implemented CANet model architecture using the same set of frames and their corresponding masks
- Tested CANet model implementation with test frames and found that U-Net model performed better compared to CANet model  
