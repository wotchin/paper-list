# Computer Vision
以有代表性的论文为主，按照通用方法和细分领域进行分类。

# Face Recognition
|Name|Comment|Published Year|
|-|-|-|
|A 3D GAN for Improved Large-pose Facial Recognition |利用GAN算法，进行数据增强，对large-pose 人脸识别有很好的性能提升 | CVPR 2021 |
|When Age-Invariant Face Recognition Meets Face Age Synthesis: A Multi-Task Learning Framework|提出了一种多任务学习框架MTLFace，提高了对年龄的抗干扰能力和跨年龄人脸图像生成 | CVPR 2021 |
|MagFace: A Universal Representation for Face Recognition and Quality Assessment|提供人脸识别、质量评估的方法| CVPR 2021 |
|Spherical Confidence Learning for Face Recognition|用于评估人脸识别的置信度|CVPR 2021|
|Cross-Domain Similarity Learning for Face Recognition in Unseen Domains|跨域的度量学习，可用于识别没有见过的人脸样本|CVPR 2021|
|Dynamic Class Queue for Large Scale Face Recognition In the Wild | 提出DCQ方法来解决计算成本和长尾分类问题，这两个问题是大规模人脸识别的难点 | CVPR 2021 |
|Mitigating Face Recognition Bias via Group Adaptive Classifier| 一种提升人脸识别准确度的方法 | CVPR 2021 |
|Pseudo Facial Generation with Extreme Poses for Face Recognition | 通过GAN，提升极端人脸姿势（如侧脸、化妆等）场景下的人脸识别精度 | CVPR 2021 |


# Network Structure
|Name|Comment|Published Year|
|-|-|-|
|Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning, by Christian S., Sergey I., Vincent V. & Alexander A A.|Inception-v4网络结构的实现|2017|


# Object Detection
|Name|Comment|Published Year|
|-|-|-|
|Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks|Fast R-CNN的实现论文|2015|
|Salient Object Detection: A Discriminative Regional Feature Integration Approach, by Huaizu J., Jingdong W., Zejian Y., Yang W., Nanning Z. & Shipeng Li.|一种经典的显著目标检测(SOD)方法，将该任务看做一个回归任务。|2013|

# Image Segmentation
|Name|Comment|Published Year|
|-|-|-|
|U-Net: Convolutional Networks for Biomedical Image Segmentation, by Olaf R., Philipp F. &Thomas B.|U-Net是一种经典的图像分割神经网络。|2015|
|Conditional Random Fields as Recurrent Neural Networks, by Shuai Z., Sadeep J., Bernardino R., Vibhav V. et al|CRF与CNN结合，输出更细粒度的图像分割边界。|2015|

# Visual Recognition and Description
|Name|Comment|Published Year|
|-|-|-|
|Long-term recurrent convolutional networks for visual recognition and description|LRCN网络的实现，融合了LSTM与CNN，能够进行图片信息描述。|2015|

# Super Resolution
|Name|Comment|Published Year|
|-|-|-|
|Image Super-Resolution Using Deep Convolutional Networks, by Chao D., Chen C., Kaiming H. & Xiaoou T. |通过CNN学习低分辨率图像到高分辨率图像的映射，从而实现图像超分辨率。|2014|


# Video Classification
|Name|Comment|Published Year|
|-|-|-|
|Beyond short snippets: Deep networks for video classification, by Joe Y. Ng, Matthew J. H., Sudheendra V., Oriol V., Rajat M. & George T.|通过训练后的CNN提取视频帧信息，将提取到的帧特征和光流特征输入到LSTM或池化层中用于分类任务。文中对比了如何提高分类效果的方法，是该领域的经典。|2015|
