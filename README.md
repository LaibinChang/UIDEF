# CUIED: A Comprehensive Underwater Image Enhancement Dataset and Beyond

[TOC]

## 1.Abstract

Although many underwater image enhancement methods have been proposed in recent years, they are mainly evaluated using either synthetic datasets or a few selected real-world images. Considering this limitation, we present a Comprehensive Underwater Image Enhancement Dataset (*CUIED*), which consists of seven categories and twelve subcategories with 18,686 real-word underwater images. These categories basically cover the multiple degradation types and diverse shooting perspectives of common underwater imaging. To demonstrate the practicability and effectiveness of this dataset, we propose a multi-scale weighted fusion enhancement framework based on the visual perception balance processing and four attentive weight maps. The visual perception balance is essential to restore the distorted color of original underwater images, while the four attentive weight maps are defined to assign high weights to specific pixels for making the enhanced output images present more important information and better visual perception. Comprehensive qualitative and quantitative empirical evaluations validate that our framework achieves better performance than other eight state-of-the-art underwater image enhancement methods in most cases. In addition, we demonstrate an additional application of *CUIED* to reconstruct a wider field of view image based on multiple input images with overlapping regions.

## 2.Paper

CUIED: A Comprehensive Underwater Image Enhancement Dataset and Beyond

## 3.Dataset

The *CUIED* dataset is collected during oceanic explorations and human-robot cooperative experiments in different locations under various visibility conditions. Specifically, we first used two different cameras included Nikon (COOLPIX AW130s) and GoPro (Hero 4), to record the 640P and 1080P underwater videos. After recording the videos, we sampled images according to the different characteristics (*e.g.*, color, perspective, and scene) from these videos to construct *CUIED*, which contains a large collection of unpaired and consecutive underwater images with a number of 18,686.

We divide the collected images into seven categories: images with distorted color, images with different perspectives, images with low contrast, images with blur perception, images with an uneven-brightness scene, images with a dim scene, and images with a turbid scene. Then, considering the difference in color distortion, the category of images with distorted color is further divided into three subcategories: the bluish appearance, the greenish appearance, and the yellowish appearance. Similarly, the images with different perspectives are composed of the downward-looking, forward-looking, and upward-looking. These images are carefully selected to accommodate a wide range of underwater degradation variability.

The raw dataset can be found completely from here. [https://pan.baidu.com/s/1YFcwSb56wZPTOTl7y0ueYw?pwd=tn3q]().

## 4.Codes

We would upload our code here as soon as possible, please wait.
