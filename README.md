<h1 align="center">Cell segmentation in colon tissue images using deep learning.</h1>

* [Overview](#overview)
* [Achievements](#achievements)
* [Awards and Recognitions](#awardsandrecognitions)
* [Full paper](#fullpaper)

___



<a name="overview"></a>
## Overview

Image segmentation is one of the most challenge tasks of computer vision. Its
main purpose is to split the input image into parts, and then the identification of those
parts. Respect to medical images, there are several methods to analyze histopathology
samples, we can find many publications about new methods even if we only look for a
specific subtopic, for example cell nuclei segmentation in colon tissue.

In this work, we propose a supervised deep learning-based model for accurate
automatic cell nuclei segmentation. Given a tissue image, it begins with a deep
convolutional neural network model to generate a probability map. Next, a threshold and
morphological operations are applied to distinguish the background and the cells. One of
the significant benefits of the proposed method is that it can be applicable to different
staining histopathology images taken of different patients. Due to the feature learning
characteristic of deep convolutional neural network and the high level shape prior
modeling, the proposed method is general enough to work properly across different
image scenario like healthy, adenoma, hyperplasia. Finally, we will validate the proposed
algorithm on several histopathology images using a range of different tissue from various
patients with differents diseases.

<a name="achievements"></a>
## Achievements

We have shown how deep learning methods can be a valuable tool for the
histopathology image analysis domain due to its innate ability to learn useful features
directly from data. In addition, we have outlined a full approach containing the necessary
methods to obtain a result using a supervised deep learning method from an unannotated
image dataset.
The approach presented here are not intended to be a final ending point towards
histological problems, but a surprisingly robust jumping off point for further research.

<a name="awardsandrecognitions"></a>
## Awards and Recognitions

This project was recognized in 2017 as one of the most important projects between Argentina and Hungary by FICH - Universidad Nacional del Litoral, and it allowed to start a collaboration between both countries. You can see the newspaper article [here](./Newspaper.jpg) o get into the full newspaper [here](https://www.unl.edu.ar/noticias/products/view/el_paraninfo_131_1).

<a name="fullpaper"></a>
## Full Paper

You can read the full paper [here](./Paper.pdf).

