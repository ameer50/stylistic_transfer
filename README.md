# stylistic_transfer

Adapted and modified from https://github.com/titu1994/Neural-Style-Transfer

Model Used: VGG 19
Tranfer Learning Approach was used: Weights were obtained from https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg19_weights_tf_dim_ordering_tf_kernels_notop.h5

Style Transfer is a mechanism that allows one to take the style of a particular painting and "repaint" a new image in that same style.

NeuralStyleTransfer.ipynb python notebook file works in conjunction with the INetwork.py python file to load pre-existing weights (derived from the above link) and implement a VGG19 model, which is essentailly a convolutional neural network with many layers. 
_____________________________________________________________________________________________________________________

***MY MAJOR MODIFICATIONS***

My expansion of this work is primarily rooted in quantitative research I performed. I analyzed how many epochs was optimal in terms of achieving an ideal painting with preserved style elements and crisp content elements. I also played around with the weights and chose to implement a max pooling algorithm for the process.

Additional experimentation I performed included feeding in rotated images to the algorithm to observe changes in final painting outputs and observing differences in the resolution of images.

Credit is due to the model that I adapted my work from (listed above). That being said, the theories behind this particular art generation including the VGG model, content and style weights, and benefits of CNN implementation are fully understood by me.
