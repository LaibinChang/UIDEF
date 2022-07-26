# CUIED: A Comprehensive Underwater Image Enhancement Dataset and Beyond

[TOC]

## 1.Abstract

Numerous underwater image enhancement methods have been proposed in recent years. However, these methods are mainly evaluated using either synthetic datasets with similar degradation or small-scale datasets with few images. It is clear that a benchmark dataset containing various degraded situations and real-world underwater images is needed to evaluate the performance of these methods. In this paper, we present a **Comprehensive Underwater Image Enhancement Dataset (CUIED)**, which consists of seven categories and twelve subcategories with 18,686 real-world underwater images. These categories roughly cover the multiple degradation types and different shooting perspectives of common underwater imaging. Using the dataset, we conduct a qualitative and quantitative empirical evaluation on eight state-of-the-art underwater image enhancement methods to reveal the effectiveness of them. Considering the limitations of these above methods, we propose a multi-scale weighted fusion enhancement framework based on the visual perception balance processing and four attentive weight maps. The visual perception balance is essential to restore the distorted color of original underwater images, while the four attentive weight maps are defined to assign high weights to specific pixels for making the enhanced output images present more important information and better visual perception. Extensive experiments validate that our framework achieves better performance than the eight methods in most cases. In addition, we demonstrate an additional application of *CUIED* to reconstruct a wider-field underwater image based on multiple input images with overlapping regions. The dataset and code are available at https://github.com/LaibinChang/CUIED.git.

## 2.Paper

CUIED: A Comprehensive Underwater Image Enhancement Dataset and Beyond

## 3.Dataset

The *CUIED* dataset is collected during oceanic explorations and human-robot cooperative experiments in different locations under various visibility conditions. Specifically, we first used two different cameras included Nikon (COOLPIX AW130s) and GoPro (Hero 4), to record the 640P and 1080P underwater videos. After recording the videos, we sampled images according to the different characteristics (*e.g.*, color, perspective, and scene) from these videos to construct *CUIED*, which contains a large collection of unpaired and consecutive underwater images with a number of 18,686.

We divide the collected images into seven categories: images with distorted color, images with different perspectives, images with low contrast, images with blur perception, images with an uneven-brightness scene, images with a dim scene, and images with a turbid scene. Then, considering the difference in color distortion, the category of images with distorted color is further divided into three subcategories: the bluish appearance, the greenish appearance, and the yellowish appearance. Similarly, the images with different perspectives are composed of the downward-looking, forward-looking, and upward-looking. These images are carefully selected to accommodate a wide range of underwater degradation variability.
![image](https://user-images.githubusercontent.com/88143736/168535408-4344d264-bd79-47b0-9897-962510411666.png)

The raw dataset can be found completely from here. [https://pan.baidu.com/s/1pQsfrdaZONvl2oyWnAetVw?pwd=UIDE]().

## 4.Codes

We would upload our code here as soon as possible, please wait.
