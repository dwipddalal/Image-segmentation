# Image segmentation
- Trained the model on the M2NIST dataset, a multi-digit MNIST. 
- Used Convoluonal Neural Network (CNN) from scratch for the downsampling path and used a Fully Convolutional Network, FCN-8, to upsample and produce the pixel-wise label map. 
![image](https://user-images.githubusercontent.com/91228207/162801619-87e188f6-cd71-4fbd-ac63-3259a63d11a4.png)


1. **Downsampling Path** - This part of the network extracts the features in the image. This is done through a series of convolution and pooling layers. The final output is a reduced image (because of the pooling layers) with the extracted features.

2. **Upsampling Path** - This takes the output of the downsampling path and generates the predictions while also converting the image back to its original size. 
