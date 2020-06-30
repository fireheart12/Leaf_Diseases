# Leaf Disease Identification

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/promotional_pic.webp)

## (I) Abstract : 

Misdiagnosis of the many diseases have a colossal impact on agricultural crops which in turn leads to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts.

Current disease diagnosis based on human scouting is time-consuming and expensive. Yesterday, I finally finished my work revolving around deep learning and computer vision to identify category of foliage diseases in apple leaves.

This project was part of Plant Pathology 2020 challenge hosted a while back on kaggle : 

**https://www.kaggle.com/c/plant-pathology-2020-fgvc7** 

## (II) Dataset Used : 

Apple orchards in the U.S. are under constant threat from a large number of pathogens and insects. Appropriate and timely deployment of disease management depends on early disease detection. Incorrect and delayed diagnosis can result in either excessive or inadequate use of chemicals, with increased production costs, environmental, and health impacts. We have manually captured 3,651 high-quality, real-life symptom images of multiple apple foliar diseases, with variable illumination, angles, surfaces, and noise. A subset, expert-annotated to create a pilot dataset for apple scab, cedar apple rust, and healthy leaves, was made available to the Kaggle community for 'Plant Pathology Challenge'; part of the Fine-Grained Visual Categorization (FGVC) workshop at CVPR 2020 (Computer Vision and Pattern Recognition). 

**https://arxiv.org/abs/2004.11958** 

The dataset is uploaded on my google drive and can also be accessed on Kaggle. Following are the links : 
* Kaggle :  *https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data*
* G-Drive : *https://drive.google.com/drive/folders/1IosfDui0TSxy22WQJuN8hYNtQWt5ocXY?usp=sharing* 

The dataset composed of about :
* 1,821 training images. Each image belonged to either of the mentioned catregory : 
  * Healthy
  * Multiple Diseased
  * Rust
  * Scab
* 1,821 testing images take from the same source distribution. Our goal was to classify these images into either of the four aforementioned classes.

Some sample images from the training dataset : 

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/sample1.jpg)
![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/sample2.jpg)
![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/sample3.jpg)
![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/sample4.jpg)

# (III) Libraries used :

## Numpy :

Fundamental package for scientific computing in Python3, helping us in creating and managing n-dimensional tensors. A vector can be regarded as a 1-D tensor, matrix as 2-D, and so on. 

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/tensor.jpg)

## Matplotlib :

A Python3 plotting library used for data visualization.

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/visualize.webp)

## Tensorflow-Keras :

Is an open source deep learning framework for dataflow and differentiable programming. It’s created and maintained by Google.

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/tf%20loves%20keras.png)

## Tqdm :

Is a progress bar library with good support for nested loops and Jupyter notebooks.

## OpenCV : 

OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms. The library is used extensively in companies, research groups and by governmental bodies.

Homepage : *https://opencv.org/*

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/opencv.png)

## Seaborn : 

Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

![](https://github.com/CodingWitcher/Leaf_Diseases/blob/master/images_for_readme/plot1.png)
