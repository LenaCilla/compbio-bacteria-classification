# Automating Microbial Colony Classification Using Neural Networks
This project uses CNN method with 4 models that are Inception-v3, DenseNet-121, VGG-16, and ResNet-50 for automating microbial colony classification to gain faster and more accurate classification results because the automatization process. The dataset that is used is [Microorganism Preprocessed Images Dataset](https://www.kaggle.com/datasets/sachinkumar413/microorganism-preprocessed-images-dataset) from Kaggle.

The result that we gained using InceptionV3 shown consistency in its performance, with the average precision and recall for all classes (macro avg) are 0.84 and 0.83 successively along with Densenet121 that also reached 0.88 accuracy, showing its ability to classify data correctly. However, VGG16only reached an accuracy of 0.72 and Resnet50 the model showed a poor performance with 0.21 accuracy. This shows that the model can not classify the instances adequately in the dataset evaluation. 

Densenet201 model has shown a high and better performance with 0.88 accuracy, which is significantly higher than ResNet that was tested before. From this experiment, we found that DenseNet architecture, with all of its features to utilize previous layers, effectively grasp important information from the microbe images, so it can raise the classification accuracy. This shows that the usage of the architecture with complex and in depth can show a significant raise in classification task such as this. 
