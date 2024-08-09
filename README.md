# Image-Captioning-Using-Deep-Learning
The contents of an image are generated automatically which involves computer vision and Natural Language Processing. It depends on computer vision and machine translation. This model is used to generate natural sentences that eventually describe the image. This model consists of Convolutional Neural Network(CNN) as well as Recurrent Neural Network(RNN). The model is trained in such a way that if input image is given to the model it generates captions which nearly describes the image. The accuracy of model and smoothness or command of language model learned from image descriptions is tested on different datasets.
Here, pre-processed images with the inception V3 model and then extracted features. It is a pre-trained CNN model with an ImageNet dataset. It was decided to look into ways to improve Inception v2 without drastically modifying the modules.
image captioning architecture consists of 3 models:
CNN
TransformerEncoder
TransformerDecoder
