# Desires and Objectives

## Introduction

"Fashion-MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes."[<sup>[1]</sup>]

As outlined on the TensorFlow website, this dataset is labelled for supervised learning. The image format is (1, 28, 28), with the first element set to 1 due to its grayscale nature which represents the number of color channels, and the image type is unit8. The labels are represented as int64.

The dataset is also available on GitHub.[<sup>[2]</sup>]

Each training and test example falls into one of the following categories:
- 0: T-shirt/top
- 1: Trouser
- 2: Pullover
- 3: Dress
- 4: Coat
- 5: Sandal
- 6: Shirt
- 7: Sneaker
- 8: Bag
- 9: Ankle boot

## Aims and Objectives

The primary goal here is to identify the most optimal model that can learn and classify based on knowledge gained from AI classes and labs conducted by Jérémie Wenger, as well as insights gained from the book "Deep Learning with Python" by François Chollet.

To accomplish this, the following strategies will be applied:
- Altering activation functions
- Modifying optimizers
- Adjusting the number of neurons in layers
- Adding a hidden layer
- Employing K-fold validation
- Employing K-fold shuffling
- Applying dropout technique
- Applying the regularization technique

## Success Criteria

Our standard model is the one provided on the TensorFlow website. Any improvements beyond this will be considered a success.
It is worth mentioning that high accuracy might not always lead to learning in our model, sometimes the model will memorise the data instead of learning (overfitting), and the memorising causes a serious problem when we try our model in a testing data, which the model have never seen before and will lead to a failure.

[1]: #References
[2]: #References
