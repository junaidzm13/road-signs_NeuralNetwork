# road-signs_NeuralNetwork

### Designed, developed and implemented an AI to identify and label traffic signs appearing in photographs.

## How to run?
  -  Run pip3 install -r requirements.txt to install this project’s dependencies: opencv-python for image processing, scikit-learn for ML-related functions, and tensorflow for neural networks.
  - Then in repo, run **python traffic.py gtsrb**
  - Please note that dataset have not been provided due to size constraints. Please download it from the source provided and rename it to *gtsrb*.
  
## Background
As research continues in the development of self-driving cars, one of the key challenges is [computer vision](https://en.wikipedia.org/wiki/Computer_vision), allowing these cars to develop an understanding of their environment from digital images. In particular, this involves the ability to recognize and distinguish road signs – stop signs, speed limit signs, yield signs, and more.

In this project, I have used [TensorFlow](https://www.tensorflow.org/) to build a neural network to classify road signs based on an image of those signs. To do so, I needed a labeled dataset: a collection of images that have already been categorized by the road sign represented in them. Several such data sets exist, but for this project, I have used the [German Traffic Sign Recognition Benchmark (GTSRB)](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) dataset, which contains thousands of images of 43 different kinds of road signs.

## Acknowledgements
  - Data provided by [J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011](http://benchmark.ini.rub.de/index.php?section=gtsrb&subsection=dataset#Acknowledgements)
  - Special thanks to CS50AI 2020: Introduction to Artificial Intelligence with Python course's managment, lecturers and tutors.
  
