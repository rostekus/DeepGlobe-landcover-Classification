# DeepGlobe-landcover-Classification
Landcover Classification and Segmetation. The number of categories is 7.

Notebook can be also found on [kaggle](https://www.kaggle.com/code/rostekus/deepglobe-land-cover-classification).
Dataset on kaggle: [Chest Xray Masks and Labels](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset)

Images was patchified into 256x256 images.
For model was used models from [segmentation models](https://github.com/qubvel/segmentation_models). It is the API for keras which
makes much easier of usage of U-net or Linknet with pretrained backbones such as VGG or ResNet.


### Dataset
Dataset contains landcover and corresponding masks.

<p align="center">
   <img src="./images/3.png" width="720">
 </p>
 
### Models
U-net was used with Resnet, Vgg16, Inceptionv3 backbones. All models was trained for 50 epochs.

<p align="center">
   <img src="./images/1.png" width="720">
</p>
 <p align="center">
   <img src="./images/2.png" width="720">
 </p>
 
