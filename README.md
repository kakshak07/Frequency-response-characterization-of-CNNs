# Frequency-response-characterization-of-CNNs

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

Similar is the structure in Fashion_MNIST folder

<br>

There is file Get_input_data_ffts_v2 which contains FFT transform for CIFAR10 and MNIST datasets.<br><br>

FFT transform is performed and average is taken for each category with plotting of images.
<br><br>

