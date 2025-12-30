# Monocular Pose and Depth Estimation

This project explores monocular pose classification and depth estimation from single RGB images using deep learning. It focuses on understanding how different neural network architectures extract spatial information from minimal visual input under challenging conditions such as blur, noise, and limited viewpoints.

Custom convolutional neural networks and pretrained models are implemented and compared across both classification and regression tasks. The work emphasises robustness, generalisation, and training strategy, including selective fine-tuning and staged unfreezing.

The results show that lightweight CNNs are highly effective for pose recognition, while pretrained architectures benefit depth estimation when carefully fine-tuned. Overall, the project demonstrates how accurate pose and depth information can be recovered from a single image without relying on multi-view geometry or additional sensors.
