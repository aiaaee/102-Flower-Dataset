# 102-Flower-Dataset with VGG16 

102Flower is an image classification dataset consisting of 102 flower categories. The flowers chosen to be flower commonly occurring in the United Kingdom. Each class consists of between 40 and 258 images.
The images have large scale, pose and light variations. In addition, there are categories that have large variations within the category and several very similar categories.

![Example-images-from-the-Oxford-102-Flowers-dataset](https://github.com/user-attachments/assets/9014374f-fcf5-477e-ac65-cb898641dec8)
 

## Downloads
The data needed for evaluation are:

[Dataset images](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz)

[Image segmentations](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102segmentations.tgz)

[&Chi2 distances](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/distancematrices102.mat) - As used in the ICVGIP 2008 publication.

[The image labels](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/imagelabels.mat)

[The data splits](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/setid.mat)

The [README](https://thor.robots.ox.ac.uk/flowers/102/README.txt) file explains everything.

![download](https://github.com/user-attachments/assets/516f3ee6-c51d-4b98-8a97-0ed16292d4b9)


## Visualization of the dataset
We visualize the categories in the dataset using SIFT features as shape descriptors and HSV as colour descriptor. The images are randomly sampled from the category.

![T_colouriso](https://github.com/user-attachments/assets/0d8d53d0-9317-421e-9f02-61c5ede954de) ![T_shapeiso](https://github.com/user-attachments/assets/078f70b0-bf8a-49c4-ac8a-695a29eb7c39)


## Publications

Nilsback, M-E. and Zisserman, A.
Automated flower classification over a large number of classes  
Proceedings of the Indian Conference on Computer Vision, Graphics and Image Processing (2008)

