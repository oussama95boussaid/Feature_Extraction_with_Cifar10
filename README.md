# Feature Extraction with Cifar10

Running this program will train feature extraction with the ( **VGG** Or **Inception** Or **Resnet** ) network/Cifar10 dataset bottleneck features. 
The 100 in **vgg_cifar10_100** Or **inception_cifar10_100** Or **resnet_cifar10_100**  indicates this file has 100 examples per class.

Here's an exemple of how you would run the vgg file from the command line:

<< python feature_extraction.py --training_file vgg_cifar10_100_bottleneck_features_train.p --validation_file vgg_cifar10_bottleneck_features_validation.p >>

After 50 epochs these are the results for each model:

VGG 
Epoch 50/50
1000/1000    [==============================] - 0s - loss: 0.2418 - acc: 0.9540 - val_loss: 0.8759 - val_acc: 0.7235
