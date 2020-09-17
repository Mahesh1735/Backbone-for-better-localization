# Backbone-for-better-localization
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An attempt to develop a better backbone for object localization.

Traditionally convolutional neural networks backbones developed for the classification task are widely used for all the computer vision-related tasks. As these networks are intended to classifiers, they may lack architecturally features that are important for other tasks like localization.

![d1](https://github.com/Mahesh1735/Backbone-for-better-localization/blob/master/Media/datasamp.png)
![d2](https://github.com/Mahesh1735/Backbone-for-better-localization/blob/master/Media/datasamp2.png)

So, this is a Pilot experiment to explore such Backbone, which is explicitly designed to excel in localization and classification. Here we created a simple localization and detection dataset using the MNIST dataset. Then we performed experiments on various simple scaled-down models to test these hypotheses.

## Experimented concepts
- Splitting the backbone into a classifier and a localizer. And by maintaining the high interconnectivity, we can merge two different architectures.
- Strategic usage of spacial max pooling and contextual max pooling.

These networks are mindfully designed to have less parameters for better performance. (Compared to the similar base models)

## Base model
<a href="url"><img src="https://github.com/Mahesh1735/Backbone-for-better-localization/blob/master/Media/strd.png" align="Center" height="500" width="210" ></a>

## With first Modification
![m2](https://github.com/Mahesh1735/Backbone-for-better-localization/blob/master/Media/mod_par.png)

## With second Modification
![m3](https://github.com/Mahesh1735/Backbone-for-better-localization/blob/master/Media/mod_net_final.png)
