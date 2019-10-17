# A Computer Vision Approach for Automatic Measurement of the Inter-plant Spacing

## Abstract

Global food demand is increasing every year and it is needed to respond to this demand. In addition, some crops such as corn, which is the most produced grain in the world, is used as food, feed, bio-energy and other industrial purposes. Thus, it is needed the development of new technologies that make possible to produce more from less land. In particular, the corn crop is sensitive to its spatial arrangement and any variation in plant distribution pattern can lead to reduction in corn production. Nowadays, the uniformity of the plant spacing is checked manually by agronomists in order to predict possible production losses. In this context, this work proposes an automatic approach for measuring the spacing between corn plants in the early stages of growth. The proposed approach is based on computer vision techniques in order to evaluate the automatic inter-plant spacing measurement from images in a simple and efficient way, allowing its use on devices with low computational power such as smart phones and tablets. An image dataset was built as an additional contribution of this work containing 2186 corn plants in two conditions: tillage after the application of herbicide (TH) with 1387 corn plants and conventional tillage (CT) with 799 corn plants. The dataset is available at url: http://github.com/Brilhador/cornspacing. The experimental results achieve 90% of precision and 92% of sensitivity in corn plant identification. Regarding the automatic measurement of the interplant spacing, the results showed no significant differences from the same measurements taken manually, indicating the effectiveness of the proposed approach in two distinct types of planting

# Dataset
## A spacing between corn plants dataset (cornspacing)

The adoption of uniform spacing between plants is one of the actions to achieve good grain production indices.

The dataset consists of 188 corn planting images distributed in two classes: tillage conventional (66) and tillage after application of herbicides (122). Each image has an xml file containing information about the image, as a class, time of  purchase, amount of plants, plant spacing in centimeters and plants demarcation coordinates. The base features auxiliary files such as images that represent the demarcation by region, demarcation of boundaries of plants and entire arrays representing the boundaries of the plant.

# Paper

Available [here](http://link.springer.com/chapter/10.1007/978-3-319-25751-8_27).

Bibtex:
```
@InProceedings{brilhador2015,
author="Brilhador, Anderson and Serrarens, Daniel A. and Lopes, Fabr{\'i}cio M.",
editor="Pardo, Alvaro and Kittler, Josef",
title="A Computer Vision Approach for Automatic Measurement of the Inter-plant Spacing",
booktitle="Progress in Pattern Recognition, Image Analysis, Computer Vision, and Applications",
year="2015",
publisher="Springer International Publishing",
address="Cham",
pages="219--227",
isbn="978-3-319-25751-8"
}
```

# Use

All data and code is subject to copyright and may only be used for non-commercial research. In case of use please cite our publication.

Contact Anderson Brilhador (andersonbrilhador@gmail.com, brilhador@utfpr.edu.br) for any questions.


