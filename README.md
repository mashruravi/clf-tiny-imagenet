# Tiny ImageNet Classifier

An image classifier trained on the Tiny ImageNet dataset as an assignment for the EIP 3.0 course.

## Summary

This assignment required training a deep neural network to perform image classification on the Tiny ImageNet dataset, subject to the following constraints:

1. At least 5 variants of image augmentation should be performed.
2. A validation score of >45% has to be obtained.
3. The network should be trained for up to 500 epochs only.
4. The network should not have more than 26 million parameters.
5. 1x1 convolutions cannot be used to increase the number of channels.
6. Dropout layers cannot be used.
7. Fully connected layers cannot be used.

## Submission details

- The following variants of image augmentation were used:

  - Rotation
  - Horizontal shift
  - Vertical shift
  - Horizontal flip
  - Vertical flip

- A validation score of **55.28%** was obtained.

- The above score was obtained by training the network for only **60 epochs**.

- The network used has **9.2 million parameters**.

- The **cyclic learning rate** scheme was used to train the neural network.

- No 1x1 convolutions, dropout, or fully connected layers were used.

Further details and complete logs of the submission are in the [A4_20.ipynb](A4_20.ipynb) file.

