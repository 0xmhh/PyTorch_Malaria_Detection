The Neural Net was trained with the wide_resnet_50 model on a GPU fom google Colab.

The model performs fairly well on the data with the following confusion matrix

                precision    recall  f1-score   support

 parasitized       0.98      0.92      0.95      1300
  uninfected       0.92      0.98      0.95      1300

    accuracy                           0.95      2600
   macro avg       0.95      0.95      0.95      2600
weighted avg       0.95      0.95      0.95      2600
