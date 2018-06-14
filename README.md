# **Signature verification model :**

**This is a Siamese based model for offline siganture verification. It utilizes convolutional neural networks and deep learning to compare an original signature sample with a test sample and predict whether the test sample is genuine or forged.**

-The code for this model has been written for direct implementation in Google Colab. Due to memory limitations, the size of the training set may be reduced.

-The CEDAR signature dataset can be uploaded in zip file format to Google Drive for direct execution.

-The model outputs a prediction value and the signatures are classified as genuine or forged depending on how small or how large the prediction value is.

-The code includes a custom-defined accuracy metric that computes the prediction accuracy of the model over the test set.

