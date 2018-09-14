

## 기본적인 Machine Learning의 용어와 개념 정리

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

<br>

<strong>Types of Supervised Learning : Training Data Set을 가지고 학습을 하는 방법의 종류</strong>
- Regression(회귀) : 주어진 Data set 안에서 어떠한 조건과 결과를 학습한 후 이것을 그래프로 만드는데 이 작업이 데이터를 반복적으로 관찰하는 작업이다. 그러면 결과값들이 패턴을 가지면서 그래프를 그리는데 이것을 회귀 그래프라 한다. 이 회귀 그래프 안에서 오차값을 줄여 어떠한 조건에서 결과값을 추출해서 반환해 주는 방법을 Regression(회귀)라고 한다. 
<br>
예 ) 공부 시간에 따른 시험점수 Training Data Set이 아래와 같다고하고 이 데이터로 학습을 했을 때 <br>
<table>
 <tr>
  <th>X(공부시간)</th><th>Y(시험점수)</th>
 </tr>
 <tr>
  <td>10</td><td>90</td>
 </tr>
 <tr>
  <td>9</td><td>80</td>
 </tr>
 <tr>
  <td>3</td><td>50</td>
 </tr>
 <tr>
  <td>2</td><td>30</td>
 </tr>
</table>
여기에서 예측할 수 있는 시험점수의 유효범위는 0~100점 사이이다.<br>
이 데이터를 가지고 학습을 시키면 Regression Model 기반의 회귀 그래프가 만들어진다.<br>
예를 들어 어떤 학생이 7시간 공부했을 때 어떤 시험점수를 받을 수 있을까 예측해보면<br>
만들어진 회귀 그래프 안에서 최대한 오차를 줄여서<br>
x=7 일때 y=65이다 라는 예측을 하는 것이다.<br>

<br>

- Binary Classification(이진분류) : 위의 Regression과는 다르게 어떠한 Data Set에 대해서 학습한 후 결과Y가 2가지 분류로 나누는 방법이다.<br>
예 ) 공부시간에 따른 시험 합격률 Data Set을 학습하여 공부시간을 던져줬을 때 시험에 합격할 수 있는지 없는지 2가지 종류(Pass or Non-pass)로 결과를 넘겨준다.

<br>

- Multi-label Classification(다중분류) : Binary Classification과 비슷하지만 이진으로 분류하지 않고 결과를 여러가지 종류로 나누는 방법이다.<br>
예 ) 공부시간에 따른 시험등급 Data Set을 학습하여 공부시간을 던져줬을 때 어떤 시험등급을 받을지(수,우,미,양,가) 결과를 넘겨준다.
