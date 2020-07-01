<h1 align="center">Image Classifier to identify Dog Breeds</h1>

<div align= "center">
<h4>A pre trained image classifier that identifies dog breeds and compares the performance of 3 different CNN model architectures ('vgg', 'alexnet', and 'resnet') to determine which one provides the best result.</h4>
</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/haardikdharma10/Dog-Breed-Classifier/issues)
[![Forks](https://img.shields.io/github/forks/haardikdharma10/Dog-Breed-Classifier.svg?logo=github)](https://github.com/haardikdharma10/Dog-Breed-Classifier/network/members)
[![Stargazers](https://img.shields.io/github/stars/haardikdharma10/Dog-Breed-Classifier.svg?logo=github)](https://github.com/haardikdharma10/Dog-Breed-Classifier/stargazers)
[![Issues](https://img.shields.io/github/issues/haardikdharma10/Dog-Breed-Classifier.svg?logo=github)](https://github.com/haardikdharma10/Dog-Breed-Classifier/issues)
[![MIT License](https://img.shields.io/github/license/haardikdharma10/Dog-Breed-Classifier.svg?style=flat-square)](https://github.com/haardikdharma10/Dog-Breed-Classifier/blob/master/LICENSE)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## Models used
- [VGG](https://arxiv.org/abs/1409.1556)
- [AlexNet](https://en.wikipedia.org/wiki/AlexNet)
- [ResNet](https://arxiv.org/abs/1512.03385)

## Pre-requisites
All the dependencies and required libraries are included in the file [requirements.txt](https://github.com/haardikdharma10/Dog-Breed-Classifier/blob/master/requirements.txt)

## Installation
```
$ git clone https://github.com/haardikdharma10/Dog-Breed-Classifier.git
```
```
$ pip3 install -r requirements.txt
```
```
$ python3 check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
$ python3 check_images.py --dir pet_images/ --arch alexnet --dogfile dognames.txt
$ python3 check_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt
```
## Authors
* **Haardik Dharma** - Initial Work
* **Udacity** - First project of the 'AI Programming with Python Nanodegree'

## License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/haardikdharma10/Dog-Breed-Classifier/blob/master/LICENSE) file for details. 
