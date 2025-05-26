<h1>Deep Learning for Facial Emotion Recognition</h1>
This project explores facial emotion recognition using deep learning, specifically through the development and optimization of Convolutional Neural Networks (CNNs) to classify grayscale facial images into two categories: "happy" and "sad."


<h2>Overview</h2>
The study focuses on progressively enhancing CNN performance through:
Architectural refinements (increased convolutional filters)
Optimization techniques (transitioning from SGD to Adam)
Activation function tuning (from Sigmoid to ReLU)
Infrastructure and framework migration (from TensorFlow on AWS to PyTorch on HDFS)

<h2>Technologies Used</h2>
PyTorch – Deep learning framework with dynamic computation graphs
HDFS – Local distributed file system used instead of AWS due to connectivity issues
Python – For data loading, preprocessing, and model development
Matplotlib – For visualizing feature maps

<h2>System Architecture</h2>
Virtual machine (CPU-only)
12GB RAM / 200GB storage (upgraded from 4GB / 120GB)
Training and inference done on grayscale 48×48 images
Three CNN models developed and evaluated with incremental improvements
