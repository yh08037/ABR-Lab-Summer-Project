# ABR-Lab-Summer-Project

```tensorflow```와 ```keras```가 통합되고, ```tensorflow```에서도 고수준의 API들이 지원되면서, 기존의 Placeholder, Session, feed_dict 구조의 기존의 ```tensorflow``` 코드가 더이상 지원되지 않을 것이라는 경고(deprecated)를 많이 보게 되었다. 따라서 이번 기회에 ```fastai```, ```keras```와 ```tensorflow 2.0```의 API을 활용해서 개인 프로젝트 과제를 수행해보기로 하였다.

image dataset을 정하여 CNN 모델을 적용하여 학습시켜 보는 것이 이번 과제의 목표이다. 처음에는 ```intel image classification``` dataset을 학습해보려 하였으나, label이 6개 밖에 되지 않는 데이터 셋이어서 label이 더 많은 dataset을 사용하기로 하였다. ```cifar 100``` 과 ```stanford dog breed dataset``` 중 고민을 하였다. dog breed classification을 수행하는 것이 2019년 1학기의 과제로 나왔었는데, 완성시키지 못하고 흐지부지된 것이 아쉬워 ```standford dog breed dataset```을 학습시켜보기로 결정하였다.

## fastai
```ciafr 10```, ```cifar 100```의 모델에 따른 정확도에 대하여 조사하면서 `ResNet`, `Inception`, `EfficientNet`, `MobileNet`등의 향상된 CNN 모델을 새로 알게 되었고, `ResNet`과 `Inception`은 `keras`나 `fastai`의 내장 모델로 구현되어 있다는 사실을 알게되었다. 매우 간결한 코드로 모델을 학습시켜볼 수 있는 `fastai`라는 모듈에 흥미가 생겨, `fastai`에 구현되어있는 모델들을 활용하여 `cifar 10` dataset을 높은 accuracy로 학습시켜 보고자 하였다.

## Image_Data_loading_and_preprocessing.ipynb
```tensorflow 2.0```의 이미지 데이터 로딩과 처리에 대한 튜토리얼을 따라하며 새로워진 기본 문법과 ```tf.keras``` 라이브러리에 대하여 알게되었다. 
