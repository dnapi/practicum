# Age recognition from an image

We developed a neural network model
for age determination of customers using their photos.

As the main model, we chose the `ResNet50` model, pre-trained on the ImageNet image dataset.
To adjust model to our need we add two extra dence layer:
- GlobalAveragePooling2D
- and dense layer with ReLu activation function.

On the test set, the `MAE` value was equal to `5.95`,
which satisfies the customer's technical requirements.
