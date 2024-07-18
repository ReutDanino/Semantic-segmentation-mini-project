We did a project in bioinformatics,
In the project we trained the UNET network as part of a semantic segmentation process.
Our goal was to enable the network to accurately create masks suitable for X-ray images of lungs.
This ability holds enormous potential for medical applications, allowing the identification and efficient analysis of conditions such as tumors or abnormalities within the lung tissues.

We started by downloading the X-ray images and their corresponding masks from Kaggle.
We trained a network referring to some important metrics - loss, iou.
We also included validation while training the network to obtain metrics that will be essential for evaluating the accuracy and reliability of our model.
To improve the performance of our network, we did augmentation - changing the images while training in order to challenge the model and prevent it from learning too well the location of the lungs. Which caused a reduction in overfitting and an improvement in the generalizability of the model to additional data.
Moreover, to optimize the process and prevent unnecessary calculation, we integrated an early stop using a callback that we wrote ourselves. This approach makes it possible to stop the training as soon as the performance indicators no longer improve significantly, thus conserving calculation resources and ensuring the model's efficiency.

Our bioinformatics mini-project not only deepened our understanding of neural network architectures, but also highlighted the potential of this world in medical diagnostics.
By using innovative technologies there is a significant contribution to the health field.
