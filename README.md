# tfClassifier

https://github.com/amusi/tfClassifier

## 使用教程

查看图像分类信息

- python classifier.py --image_file Datasets/samples/street.jpg

查看图像分类信息，并列出评分前５的分类信息

- python classifier.py --image_file inception/street.jpg --num_top_predictions 5



Reference: http://www.p5w.net/weyt/201707/t20170731_1900138.htm



## 项目内容

This repository contains code to: 
1) setup the tensorflow imagenet classifier which is capable of identifying 1000 objects.
2) setup a retraining script that takes in your own images and trains a new mdoel that you can use.
3) Using tensorflow to build a text classification system.



## 重新训练

setting up tensorflow classifier and retraining it 

find the tutorials here:
1) https://sourcedexter.com/quickly-setup-tensorflow-image-recognition/
2) https://sourcedexter.com/retrain-tensorflow-inception-model/
3) https://sourcedexter.com/tensorflow-text-classification
