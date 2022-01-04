# Advanced Machine Learning

The final group project of Advanced Machine Learning. 

Dataset: https://www.kaggle.com/lantian773030/pokemonclassification

To run the following files, you should download the dataset and put it in a folder called PokemonData in this directory.

## 30 class pokemon
For this file, we only use 20% of the data to train our network.

## pokemon_data_aug
This file compares differnet methods of data augmentation and their combaniation on training set and validation set.

## compare_dropout_baseline
This file compares different dropout rate with baseline model.

## GAN
This file is to generate 36 fake images by using DCGAN on real images. reference: https://www.tensorflow.org/tutorials/generative/dcgan?hl=zh-cn

## model
This file contians train, test, val set split. convert them to tensorflow dataset. Then apply learing rate deacy, learning rate reduction and ResNet50, mobilenet and our final model.