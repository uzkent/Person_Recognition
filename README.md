The deep learning model refered by ZFNet [1] (improved version of the AlexNet) is used as the model to transfer learning from.
We fine-tune this model on person recognition challegne. To do this, the ZFNet is trained on the different parts of human
body to learn contextual features. We fine-tune ZFNet on four different parts of human body.

  1. Extended Head Area
  2. Upper Half Body Area
  3. Global Full Body Area.
  4. Full Scene Area.
  
The fine-tuning is performed on the People in Photo Albums Dataset (PIPA) [2]. 

[1] - Zeiler, Matthew D., and Rob Fergus. "Visualizing and understanding convolutional networks." In European conference on computer vision, pp. 818-833. Springer International Publishing, 2014.

[2] - Zhang, Ning, Manohar Paluri, Yaniv Taigman, Rob Fergus, and Lubomir Bourdev. "Beyond frontal faces: Improving person recognition using multiple cues." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 4804-4813. 2015.
Harvard	
