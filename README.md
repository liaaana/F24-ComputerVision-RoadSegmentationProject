# Road Segmentation for Autonomous Vehicles 

## About the Project


This project addresses the problem of road segmentation in autonomous driving, a task essential for ensuring safe navigation and accident prevention. We implement and compare three models: a Fully Convolutional Network (FCN) based on the VGG16 architecture (without fully connected layers), a U-Net model, and a fine-tuned Segformer model, adapted for road segmentation tasks. 

The models were trained on the KITTI dataset and evaluated using the Intersection over Union (IoU) loss function. This comparative study aims to enhance understanding of model performance for pixel-wise segmentation. The results demonstrate the usefulness of state-of-the-art segmentation techniques in advancing the safety and functionality of autonomous vechicles.

## Results

The segmentation performance of U-Net, FCN, and SegFormer was evaluated. FCN exhibited lower evaluation metrics and produced more pixelated results, indicating limitations in capturing fine-grained details. U-Net demonstrated more stable and well-defined segmentations, attributable to its encoder-decoder CNN architecture that preserves spatial context. SegFormer, while achieving competitive results, showed a bias towards its original pretrained weights due to fine-tuning on a limited number of epochs, suggesting insufficient adaptation to the target dataset.

### FCN outputs
![fcn1](./results/fcn1.png)
![fcn2](./results/fcn2.png)
![fcn3](./results/fcn3.png)
### U-net outputs
![unet1](./results/unet1.png)
![unet2](./results/unet2.png)
![unet3](./results/unet3.png)
### SegFormer outputs
![segformer1](./results/segformer1.png)
![segformer2](./results/segformer2.png)
![segformer3](./results/segformer3.png)
