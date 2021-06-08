# Convolutional Neural networks comparison in covid incidence detection
Abel R, David Alejandro T, Jaqueline P and Alec G


This paper aims to compare the different state-of-the-art neural network performances in binary detection of the novel covid-19. We will be using Xception, VGG16, MobileNetV3, EficientNetB0, and NasNetMobile to make our comparison, working with approximately 4,000 Ches X-ray (CXR) images as our dataset. We obtain the quality measures (Accuracy, Precision, Recall, F1-score), confusion matrix, and the receiver operating characteristic curve (ROC curve) and provide a result analysis, summarizing the best achievements, based on volume size and true positive rate. Finally, we conclude with a discussion and future related work.

Next, we summarize the main results of our experiment...
|                |  Positive |        |          |  Negative |        |          | Accuracy | Parameters  (Millions) |
|----------------|:---------:|:------:|:--------:|:---------:|:------:|:--------:|:--------:|------------------------|
|                | Precision | Recall | F1-Score | Precision | Recall | F1-Score |          |                        |
| Xception       |    0.97   |  0.97  |   0.97   |    0.97   |  0.97  |   0.97   |   0.97   |          21.3          |
| EfficientNetB0 |    0.97   |  0.96  |   0.96   |    0.96   |  0.97  |   0.96   |   0.96   |          3.996         |
| NasNetMobile   |    0.96   |  0.95  |   0.96   |    0.95   |  0.96  |   0.96   |   0.96   |         13.483         |
| VGG16          |    0.96   |  0.95  |   0.96   |    0.95   |  0.96  |   0.96   |   0.96   |         0.02508        |
| MobileNetV3    |    0.95   |  0.95  |   0.95   |    0.95   |  0.95  |   0.95   |   0.95   |          4.203         |
