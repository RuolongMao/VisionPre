# VisionPre
Develop an initial model, using some real images from the "LungCancer4Types-ImageDataset" for lung cancer detection results and fine-tuning to enhance the accuracy of classification performance. At the same time, self-machine learning adjustment capabilities based on self-training verification were developed.

# Scripts/Commands
**1. Setup and Preparations**
This step includes importing necessary libraries, defining data transformations, and preparing your datasets.
E.g. (ResNet)
![image](https://github.com/RuolongMao/VisionPre/assets/94766074/5eccd95b-5110-4d38-8064-4ea474ad40be)

**2. Model Definition**
Set up the model, loss function, optimizer, and any learning rate schedulers or regularization techniques.
E.g. (ResNet)
![image](https://github.com/RuolongMao/VisionPre/assets/94766074/bef9e3e5-4d2d-4aa5-ae3d-cfb32a2acb63)

**3. Training**
Run the training loop, applying the early stopping mechanism if needed.
E.g. (ResNet)
![image](https://github.com/RuolongMao/VisionPre/assets/94766074/9008bfbb-69bf-44ee-a12a-d7331d40c7be)

**4. Evaluation**
Evaluate the model on the test dataset and potentially compute the confusion matrix.
E.g. (ResNet)
![image](https://github.com/RuolongMao/VisionPre/assets/94766074/b2049b24-154c-4a90-ad82-d2c74e7e8c8a)


**5. Visualizing Results**
Optionally, plot metrics such as loss and accuracy, or the confusion matrix.
E.g. (ResNet)
![image](https://github.com/RuolongMao/VisionPre/assets/94766074/a5809ad2-63ef-4654-b60b-a298950d76b7)

**Contribution**
CNN / DenseNet - Siyuan Bao
ConvNext - Peter Qiu
Resnet - Ruolong Mao
