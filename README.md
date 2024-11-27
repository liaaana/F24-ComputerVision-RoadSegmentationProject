# Road Segmentation for Autonomous Vehicles 

This project addresses the problem of road segmentation in autonomous driving, a task essential for ensuring safe navigation and accident prevention. We implement and compare three models: a Fully Convolutional Network (FCN) based on the VGG16 architecture (without fully connected layers), a U-Net model, and a fine-tuned Segformer model, adapted for road segmentation tasks. The models were trained on the KITTI dataset and evaluated using the Intersection over Union (IoU) loss function. This comparative study aims to enhance understanding of model performance for pixel-wise segmentation.  We successfully implemented and compared three models: VGG16 based FCN model, U-Net, and a fine-tuned SegFormer. Using the KITTI dataset, we evaluated their performance with the Intersection over Union (IoU) metric. While FCN was the fastest but provided poor results (IoU: 0.1786). SegFormer achieved the highest segmentation accuracy (IoU: 0.0506), demonstrating its effectiveness for complex tasks. U-Net provided a balance between computational efficiency and segmentation performance (IoU: 0.0862), making it a versatile choice. Obtained results highlight the trade-offs between speed and accuracy in the field of semantic segmentation tasks.
## Model Weights

- [FCN](https://drive.google.com/file/d/1ZWJ1y4rOyzD5dNCCY8oAGNRhH1CpqVsQ/view?usp=drive_link)
- [UNet](https://drive.google.com/file/d/1365dIP9GsIpd1UcNVZaBYWQZIzn6d6hc/view?usp=drive_link)
- [SegFormer](https://drive.google.com/file/d/1ZWJ1y4rOyzD5dNCCY8oAGNRhH1CpqVsQ/view?usp=drive_link)
