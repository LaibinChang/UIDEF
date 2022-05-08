# ERUID-A-Comprehensive-Underwater-Image-Dataset

[TOC]

## 1.Abstract

In this paper, we present a comprehensive underwater image dataset for perceptive enhancement and visual reconstruction (*ERUID*), which consists of seven categories and twelve subcategories with 18,636 real-word underwater images. To demonstrate the practicability and effectiveness of the dataset, we successively propose a multi-scale weighted fusion enhancement framework and a mesh-optimized visual reconstruction paradigm for it. Specifically, the former (`enhancement framework`) combines the visual perception balance processing and four attentive weight maps to cope with the multiple degradation types of underwater images. Based on the results acquired by qualitative and quantitative evaluation, they validate that our framework achieves better performance than other several state-of-the-art underwater image enhancement methods in most cases. Since these images are acquired from consecutive frames and have continuous overlapping regions, the latter (`reconstruction paradigm`) reconstructs a wide-filed underwater vision by registering multiple input images based on the mesh optimization. The test images used in both of their experiments are from our *ERUID* dataset.

## 2.Paper

ERUID: A Comprehensive Underwater Image Dataset for Perceptive Enhancement and Visual Reconstruction

## 3.Dataset

The *ERUID* dataset is collected during oceanic explorations and human-robot cooperative experiments in different locations under various visibility conditions. Specifically, we first used two different cameras included Nikon (COOLPIX AW130s) and GoPro (Hero 4), to record the 640P and 1080P underwater videos. After recording the videos, we sampled images according to the different characteristics (*e.g.*, color, perspective, and scene) from these videos to construct *ERUID*, which contains a large collection of unpaired and consecutive underwater images with a number of 18,686.

We divide the collected images into seven categories: images with distorted color, images with different perspectives, images with low contrast, images with blur perception, images with an uneven-brightness scene, images with a dim scene, and images with a turbid scene. Then, considering the difference in color distortion, the category of images with distorted color is further divided into three subcategories: the bluish appearance, the greenish appearance, and the yellowish appearance. Similarly, the images with different perspectives are composed of the downward-looking, forward-looking, and upward-looking. These images are carefully selected to accommodate a wide range of underwater degradation variability.

The raw dataset can be found completely from here. [https://pan.baidu.com/s/1YFcwSb56wZPTOTl7y0ueYw?pwd=tn3q]().

## 4.Codes

We would upload our code here as soon as possible, please wait.
