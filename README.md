# Face-Detection-Using-MATLAB
This project i worked with my team was to make a face recognition model and identify face features
As a group we developed a MATLAB program using deep network designer to identify our faces in real time testing process using convolutional neural network, the project listed as a face recognition model that use backpropagation in training process
## Type of the used NN
The type of the used neural network is supervised neural network
## training method used stochastic gradient decent with
we used gradient decent with momentum (feed forward Backpropagation)

Recognition algorithms can be divided into two main approaches:
geometric, which looks at distinguishing features, or photo-metric,
which is a statistical approach that distills an image into values and
compares the values with templates to eliminatevariances. Some
classify these algorithms into two broadcategories: holistic and
feature based models. The formerattempts to recognize the face in its
entirety while the feature based subdivide into components such as
according to features and analyze each as well as its spatial location
with respect to other features.
been published at various points in the past (see list of scientific
journals). Most journals are highly specialized, although some of the
oldest journals such as Nature publish articles and scientific papers
across a wide range.


CNN are usually and more frequently used with image recognition applications because it
tends to be more accurate and powerful in the ways of solving classification problems,
therefore we will mention the main topics about it.
CNN are distinguished from other neural networks by their superior performance with
image, speech,
or audio signal inputs. They have three main types of layers, which are:
• Convolutional layer
• Pooling layer
• Fully connected (FC) layer
The convolutional layer is the first layer of a convolutional network. While convolutional
layers can be followed by additional convolutional layers or pooling layers, the fully
connected layer is the final layer. With each layer, the CNN increases in its complexity,
identifying greater portions of the image. Earlier layers focus on simple features, such as
colors and edges. As the image data progresses through the layers of the CNN, it starts to
recognize larger elements or shapes of the object until it finally identifies the intended
object.



The convolutional layer is the core building block of a CNN, and it is where
most of the computation occurs. It requires a few components, which are
input data, a filter, and a feature map. Let’s assume that the input will be a
color image, which is made up of a matrix of pixels in 3D. This means that the
input will have three dimensions—a height, width, and depth—which
correspond to RGB in an image. We also have a feature detector, also known
as a kernel or a filter, which will move across the receptive fields of the image,
checking if the feature is present. This process is known as a convolution.
The feature detector is a two-dimensional (2-D) array of weights, which
represents part of the image. While they can vary in size, the filter size is
typically a 3x3 matrix; this also determines the size of the receptive field. The
filter is then applied to an area of the image, and a dot product is calculated
between the input pixels and the filter. This dot product is then fed into an
output array. Afterwards, the filter shifts by a stride, repeating the process
until the kernel has swept across the entire image. The final output from the
series of dot products from the input and the filter is known as a feature map,
activation map, or a convolved feature.

![image](https://github.com/user-attachments/assets/3b83ef76-1ee7-4c71-b7ef-291df4ce59a7)



As you can see in the image above, each output value in
thefeature map does not have to connect to each pixel
value in theinput image. It only needs to connect to the
receptive field,where the filter is being applied. Since the
output array does notneed to map directly to each input
value, convolutional (andpooling) layers are commonly
referred to as “partiallyconnected” layers. However, this
characteristic can also bedescribed as local
connectivity. Note that the weights in the feature
detector remain fixed as it moves across the image,
which is also known as parameter sharing. Some
parameters, like the weight values, adjust during training
through the process of backpropagation and gradient
descent. However, there are three hyperparameters
which affect the volume size of the output that need to
be set before the training of the neural network begins.
These include:
1. The number of filters affects the depth of the output.
For example, three distinct filters would yield three
different features maps, creating a depth of three.
2. Stride is the distance, or number of pixels, that the
kernelmoves over the input matrix. While stride values of
two or greater is rare, a larger stride yields a smaller
output.
Zero-padding is usually used when the filters do not fit
the input image. This sets all elements that fall outside of
the input matrix to zero, producing a larger or equally
sized output.

Different trails of trainning  
![image](https://github.com/user-attachments/assets/0faa2055-9cf9-4b87-bdb7-5e35e77f5375)
![image](https://github.com/user-attachments/assets/0cab2893-3865-4b45-8824-2b09d8fbaea0)
![image](https://github.com/user-attachments/assets/a392feb7-c370-45ed-901a-afcf15fc5435)

Results:
![image](https://github.com/user-attachments/assets/5cca8309-fad7-4dac-9071-9fd1b328ba06)
