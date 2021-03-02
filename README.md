# ImageClassificationUsingPytorch
 use a pre-trained Convolutional Neural Network, and replace the last layers for the purpose of classifying custom data.
 
This is an image classification exercise using PyTorch. The model uses a pre-trained Convolutional Neural Network, such as DENSENET or VGG19, where the (fully connected) last layers are replaced for the purpose of classifying different types of flowers. Only the FC layers parameters are trained, while the CNN parameters are kept constant. The data is split up into a training and test set, the training set is used to train the network, and then predictions are made using the test set. Checkpointing, data augmentation and transfer learning are relevant features for this work. For the software components used in this project you can check the following repositories that show specific use cases:
- Neural Network training and inference on Pytorch using the F_MNIST dataset:  https://github.com/joepareti54/F_MNIST_train_inference_validation
- Pytorch checkpointing: https://github.com/joepareti54/Pytorch_model_checkpoint
 
The accuracy measured on the test set was up to 82% 

 
