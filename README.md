# Fashion Recommendation

In this project, I create an end-to-end solution for large-scale clothing retrieval and visual recommendation on fashion images. More specifically, my system can learn the important regions in an image and generate diverse recommendations based on such semantic similarity.  
In this project, I created an end-to-end solution for large-scale image classification and visual recommendation on fashion images. More specifically, my model can learn the important regions in an image and generate diverse recommendations based on such semantic similarity.  

First, I built a clothing image classification model using a ResNet-based model. The feature layer of this model can capture fine-grained semantic clothing features like fabrics, styles and patterns of the clothes. Then, using such features, the model can recommend similar clothes to the input images using nearest neighbor search.

An accompanied blog post via FloydHub can be found at this link: [Recommending Similar Fashion Images with Deep Learning](https://blog.floydhub.com/similar-fashion-images/)

## Dataset
[DeepFashion](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html) is a large-scale clothes database that is quite popular in the research community. It contains over 800,000 diverse fashion images ranging from well-posed shop images to unconstrained consumer photos. It is annotated with rich information of clothing items. It also contains over 300,000 cross-pose/cross-domain image pairs.
