# Deteccion-Covid
Neural networks for covid detection

Next, we summarize the main results of our experiment...

|                |  Positive |        |          |         |  Negative |        |          |         | Accuracy | Parámetros |
|----------------|:---------:|:------:|:--------:|---------|:---------:|:------:|:--------:|---------|:--------:|------------|
|                | Precision | Recall | F1-Score | Support | Precision | Recall | F1-Score | Support |          |            |
| Xception       |    0.97   |  0.97  |   0.97   |   217   |    0.97   |  0.97  |   0.97   |   215   |   0.97   | 21,332,010 |
| EfficientNetB0 |    0.97   |  0.96  |   0.96   |   217   |    0.96   |  0.97  |   0.96   |   215   |   0.96   | 3,996,402  |
| NasNetMobile   |    0.95   |  0.95  |   0.95   |   217   |    0.95   |  0.95  |   0.95   |   215   |   0.95   | 13,483,842 |
| VGG16          |           |        |          |         |           |        |          |         |          |            |
| MobileNetV3    |           |        |          |         |           |        |          |         |          |            |
