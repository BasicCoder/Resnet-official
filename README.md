# Resnet-official
## 1. Environment configuration
> - Ubuntu 14.04.5 LTS
> - Python 3.5
> - Tensorflow 1.4.0
## 2. Code:
TFRecord generation:
> - DataGenTFRecord.py From raw data generation TFRecord


Model build:
> - resnet_model.py : build ResNet Model

Train Model:
> - imagenet_main.py : train model

## 3. Data:
Sketchy dataset

## 4. Run:
### 1). Generation TFRecord:
> - python DataGenTFRecord.py
### 2). Train Model:
> - sh train_resnet.sh