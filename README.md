#Fashion Recommendation

In this project, I created an end-to-end solution for large-scale image classification and visual recommendation on fashion images. More specifically, my model can learn the important regions in an image and generate diverse recommendations based on such semantic similarity.

First, I built a clothing image classification model using a ResNet-based model. The feature layer of this model can capture fine-grained semantic clothing features like fabrics, styles and patterns of the clothes. Then, using such features, the model can recommend similar clothes to the input images using nearest neighbor search.

An accompanied blog post via FloydHub can be found at this link: Recommending Similar Fashion Images with Deep Learning

Dataset
DeepFashion is a large-scale clothes database that is quite popular in the research community. It contains over 800,000 diverse fashion images ranging from well-posed shop images to unconstrained consumer photos. It is annotated with rich information of clothing items. It also contains over 300,000 cross-pose/cross-domain image pairs.

More specifically, I used the images in the DeepFashion Attribute Prediction subset. It contains 289,222 number of clothes images, 50 number of clothing categories, and 1,000 number of clothing attributes. Each image is annotated by bounding box and clothing type.

AttributePrediction

Code
preprocessing.py: This code is used to pre-process the dataset.
hyper_parameters.py: This code is used to define all hyper-parameters regarding training.
fashion_input.py: This code is used to pre-process the image further during training.
simple_resnet.py: This code is used to define ResNet architecture.
train_n_test.py: This code is used as the main training file.
Sample Results
1 - Romper Category

Romper

2 - Jacket Category

Jacket

3 - Blouse Shirt Category

BlouseShirt

Requirements
TensorFlow latest version
pandas latest version
numpy latest version
