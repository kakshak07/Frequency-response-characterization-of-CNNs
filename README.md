# Frequency-response-characterization-of-CNNs
Numerous recent and popular publications on deep learning investigate specific short-comings and biases of CNN models. Often, such short-comings are closely related to the distribution of frequency components in the training data, or the frequency response of the convolutional layers in the network. For example, many adversarial attacks can be classified based on their spectral density, and may be ameliorated by suppressing high frequencies in the input. Similarly, smoothing the output of convolutional layers to remove aliasing effects consistently improves the performance of CNNs.

In this project, we aim to find concrete links between input statistics, learned convolutional filter statistics and classification performance. Specifically, we will first investigate the anatomy of frequency responses in different, existing CNN architectures and identify characteristics which lead to robust and improved classification performance. Driving from previous work we would eventually like to develop a learning scheme based directly on optimizing the frequency response characteristics of different layers, by using convolutional filters which act as bandpass filters.

## Structures of the Folders

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Folder Structure Explanation:

Main folder Contains:

1. CIFAR10
2. Fashion_MNIST

In CIFAR10 there are various files<br><br>
a. ResNet 20 model<br>
b. Gaussian Filter with Sigma = 2<br>
c. Gaussian Filter with Sigma = 4<br>
d. Gaussian Filter subtracting from orginal image (sigma = 2)<br>
e. Gaussian Filter subtracting from orginal image (sigma = 4)<br>
f. CIFAR-10 with Fourier Transform and visualizing its frequency of trained model.<br>
Similar is the structure in Fashion_MNIST folder

<br>

There is file Get_input_data_ffts_v2 which contains FFT transform for CIFAR10 and MNIST datasets.<br><br>
Select 0 for getting Fashion_MNIST Fourier Transform.<br><br>
Select 1 for getting CIFAR10 Fourier Transform.<br><br>
FFT transform is performed and average is taken for each category with plotting of images.
<br><br>

