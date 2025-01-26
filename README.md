# KI_BSc_Thesis
Thesis I did for my bachelor 'Kunstmatige Intelligentie' at Universiteit Utrecht.

This repository contains auxiliary files and Jupyter notebooks, namely:
- VGG-11, notebook for training a VGG-11 with transfer learning
- ResNet, similar notebook for ResNet
- Vision Transformer, finetuning a ViT model
- Attention rollout visualizer


The training data and the trained models are not present, due to those being restricted. <br>
Also note this is why a lot of the data preprocessing cells are not ran, to prevent the dataset from showing.<br>
If you want to use these notebooks, your own dataset has to be provided in the form of a .csv file as described in the paper.


*Abstract* <br>
This paper examines three types of models for image classification of a picked up litter dataset. A VGG, ResNet and Vision Transformer are used to compare accuracy and training time on a dataset of roughly 100.000 images. The three pretrained model types were fine-tuned on the dataset. For the VGG and ResNet, this is accomplished by transfer learning, where the model is frozen, and the classifier is trained on the newly defined classes. For the Vision Transformer, a similar process, but one where the inner weights of the Transformer are updated, is used. After training and comparing these models, the newer Vision Transformer attained an accuracy of 84%, while the older ResNet and VGG were limited to around 55% accuracy.  This difference can be explained by the different architecture, as well as the efficacy of the fine-tuning process within the Vision Transformer. This suggests the attention mechanism within the Transformer is responsible for the accuracy gain.



Luka de Vrij <br>
(2025/01/26)