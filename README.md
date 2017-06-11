The deep learning model refered by ZFNet [1] (improved version of the AlexNet) is used as the model to transfer AlexNet weights. We fine-tune this model on person recognition challegne. To do this, the ZFNet is trained on the different parts of human body to learn contextual features. We fine-tune ZFNet on four different parts of human body.

<ol>
 <li> Face-only Area (FaceNET [3])
 <li> Extended Head Area (ZFNET)
 <li> Upper Half Body Area (ZFNET) 
 <li> Full Body Area (ZFNET)
</ol>

![Alt text](./Training_ZFNET.png?raw=true "Title")
 
The fine-tuning is performed on the People in Photo Albums Dataset (PIPA) [2]. To fine-tune ZFNet, we assign zero learning rates to all the layers other than the final classification layer. Also, to fine-tune ZFNet, we could reduce the learning rates of those layers instead of making them zero.

[1] - Zeiler, Matthew D., and Rob Fergus. "Visualizing and understanding convolutional networks." In European conference on computer vision, pp. 818-833. Springer International Publishing, 2014.

[2] - Zhang, Ning, Manohar Paluri, Yaniv Taigman, Rob Fergus, and Lubomir Bourdev. "Beyond frontal faces: Improving person recognition using multiple cues." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 4804-4813. 2015.
Harvard	

[3] - Schroff, Florian, Dmitry Kalenichenko, and James Philbin. "Facenet: A unified embedding for face recognition and clustering." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 815-823. 2015.
