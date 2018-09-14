# Deep-Learning-Study
Deep Learning Study 기록물 <br>
참고 : https://hunkim.github.io/ml/


## 1일차 
> 기본적인 Machine Learning의 용어와 개념 정리

<br>

### ML(Machine Learning)의 용어와 개념 설명

> Explicit programming?
* 개발자가 어떠한 조건에 맞춰서 일일이 어떻게 대응해야하는지 프로그래밍 하는 방식을 말함.

<br>

> 그럼 Machine Learning이란?
* 개발자가 수많은 룰에 대해서 대응책을 만들어주기 힘드니까 일일이 프로그래밍 하지말고 어떤 데이터나 현상에 대해서 학습을 해서 어떻게 대응해야할지 스스로 배울 수 있도록 해보면 어떨까? 라고해서 나온 개념. Arthur Samuel 이라는 사람이 먼저 제안함.

<br>

### 머신러닝을 할때 프로그램이 스스로 학습을 해야하는데, 그 학습하는 방법에 대해서 아래의 2가지로 나누어짐.
- <strong>Supervised Learning</strong> : 어떤 하나의 레이블들이 정해져있는 데이터(Training Data Set)를 가지고 학습을 하는 방법. 
  * 예 ) 먼저 고양이 그림들을 모아 프로그램에게 주어서 학습을 시킨 후 임의의 사진을 주어서 이것이 고양이 그림인지 판별하도록 학습시키는 것(Image Labeling), 스팸 이메일을 자동으로 판별해주는것, 
- <strong>Unsupervised Learning</strong> : 어떠한 레이블이 짜여진 모델이 없이 주어진 데이터를 보고 스스로 학습하도록 하는 방법. 
    * 예 ) Google news grouping, Word clustering

<br>

<strong>Training Data Set?</strong>
- 이미 특징과 답이 정해져있는 데이터
- Supervised Learning을 하기 위해서 필요한 Data Set

