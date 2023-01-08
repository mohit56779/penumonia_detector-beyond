# penumonia_detector-beyond

## Links

Deoloyed Web app - [Link to web app](https://aguaqdni26ffvn62.anvil.app/3IYTWBJHBSYZXHENWIEATWFT)

Google Colab Notebook - [Link to google colab Notebook](https://colab.research.google.com/drive/1X7K9g7yntXIJ18A4mAaa6qWb03ghPzCx?usp=sharing)

Penumpnia Dataset used for Training - [Link to Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Accuracy

Classification Accuracy Achieved on Test Set - 92%


## Problem


Everyday nearly 2,200 children die from Pneumonia under the age of 5 (Over 15% of all deaths under the age of 5). Penumonia a curable and preventable disease. If Diagnosed in time, these deaths can be prevented. 

Currently, Diagnosis of Pneumonia requires a highly trained specialist. Even for specialists it is hard to diagnose as pneumonia manifests as increased opacity in X-rays and multiple complications like fluid overload, bleeding etc. can make it hard to detect. 

This issue is more severe especailly in developing countries where specialists are not readily available for these diagnosis causing a large number of deaths from this curable disease.


## Proposed Solution Through Computer Vision and Machine Learning

Computer Vision can help diagnose Pneumonia with a very high level of accuracy (near perfect accuracy can be achieved as per research with sufficient training and Data). 

This can help save millions of lives every year!


## Architecture 

Architecture used in this model is Densenet121 with 121 trainable layers. 

Trained for 5 epochs with Nvidia A100 GPU in Google Colab to achieve 92% accuracy on the test set.


