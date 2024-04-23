# UIDEF: A Real-world Underwater Image Dataset and A Color-Contrast Complementary Image Enhancement Framework

[TOC]

## 1.Abstract

Numerous underwater image enhancement methods have been proposed in recent years. However, these methods are mainly evaluated using synthetic datasets with similar degradation or real-world datasets with insufficient images. A benchmark dataset containing various degraded situations and real-world underwater images is needed to evaluate the performance of these methods. In this paper, we propose a Real-world Underwater Image Dataset (UIDEF), which consists of seven categories and eleven subcategories with 9200 real-world underwater images. These categories roughly cover the multiple degradation types and different shooting perspectives of common underwater imagery. Using this dataset, we conduct a qualitative and quantitative empirical comparison of eight state-of-the-art underwater image enhancement methods to evaluate their effectiveness and robustness. Considering that these methods cannot handle both color restoration and contrast enhancement of the underwater degraded images well, we present a color-contrast complementary image enhancement framework that consists of the adaptive color perception balance and multi-scale weighted fusion. The former procedure is essential to remove the color cast of original input images, while the latter defines four attentive weight maps for making the enhanced output images present a more comfortable visual perception. Extensive experiments have validated that our framework achieves relatively satisfactory
performance in most cases. In addition, we demonstrate an additional application of UIDEF in reconstructing a wider-field underwater image based on multiple images with overlapping regions.

## 2.Keywords

Underwater image enhancement; Real-world underwater dataset; Adaptive color balance; Multi-scale weighted fusion; Visual reconstruction.

## 3.Dataset

The *UIDEF* dataset is collected during oceanic explorations and human-robot cooperative experiments in different locations under various visibility conditions. Specifically, we first used two different cameras to record the 640P and 1080P underwater videos. After recording the videos, we sampled images according to the different characteristics (*e.g.*, color, perspective, and scene) from these videos to construct *UIDEF*, which contains a large collection of unpaired and consecutive underwater images with a number of 9200.

We divide the collected images into seven categories: images with distorted color, images with different perspectives, images with low contrast, images with blur perception, images with an uneven-brightness scene, images with a dim scene, and images with a turbid scene. Then, considering the difference in cast color, the images with distorted color are further divided into three subcategories of bluish appearance, greenish appearance, and yellowish appearance. Similarly, the images with different perspectives are further divided into three subcategories of downward-looking, forward-looking, and upward-looking based on the shooting perspective. These images are carefully selected to accommodate a wide range of underwater degradation variability.

This dataset contains three color casts, three captured perspectives, three complex scenes, low contrast due to scattering, and blur perception caused by camera shake, which basically covers the multiple degradation types and different shooting perspectives of common underwater imagery.

![image](https://user-images.githubusercontent.com/88143736/168535408-4344d264-bd79-47b0-9897-962510411666.png)

The raw underwater image dataset can be found from [Google Drive](https://drive.google.com/drive/folders/1uWwTHk2Sfw7GcJcqisklIFhhkrqZeqzv?usp=sharing) or [Baidu Netdisk](https://pan.baidu.com/s/1pQsfrdaZONvl2oyWnAetVw?pwd=UIDE).

**If the project is helpful to you, please cite our paper. Thanks!.**

Chang L, Song H, Li M, et al. UIDEF: A real-world underwater image dataset and a color-contrast complementary image enhancement framework[J]. ISPRS Journal of Photogrammetry and Remote Sensing, 2023, 196: 415-428.
