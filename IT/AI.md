Tensorflow 2.0 on Backend.AI

Neuron : Biological Inspiration for Computing.
  신경망


Artificial Neuron : 인공신경망


Single Perceptron -> Multi perceptron == neural network 

numerical computation using data flow graphs

Neural Network as a Computational Graph

What needs to take off Deep Learning?

keras : meta-framework ; 프레임워크의 프레임워크

tensorflow 2.0 - tensorflow+keras 


데이터/연산자 따로..

import tensorflow as tf
a = tf.add(3,5)
sess = tf.Session()
print(sess.run(a))


define & run 구조

Deep learning is representation learning.

before TF 2.0

cpu/gpu/tpu

tpu : 구글내부개발




### TensorFlow 2.0

#### TensorFlow 

 - TensorFlow Lite
 - TensorFlow.Data (1.8 ~)
 - Distributed Tensorflow
 - TF Hub (alpha)
 - TensorFlow.js (beta)
 

##### TensorFlow.Data
 - 빠르고 유연하면 사용이 편리한 입력 파이프라인
 - ETL 과정이 최적화 유도
 - Extract - Transform - Load 
 
##### TF Hub
 - 훈련된 코드 공유를 위한 머신러닝 허브
 - 조만간 새로운 사이트로 바뀔 예정
 - 머신러닝 공유 : ImageNet
 - 유효화 모델 가능 - 모델을 만들어진 시간만큼의 비용
 
##### TensorFlow.js
 - 브라우저 레벨에서의 에지 디바이스 머신러닝 
 - 노드js 기반  
 - 브라우저 기계학습

##### ML Kit
 - 머신러닝을 위한 구글의 SDK
 - 파이어베이스와 통합되어 있음
 - ios 및 안드로이드 지원

### 2.0 변경된 내용
- Eager 모드
- API 정리
- 전역 객체의 제거 / 변수 형식의 변경
- 세션 제거
- 분산 훈련 통합
- GPU 가속


### Backend.AI 소개
- www.backend.ai

Estimator : 평가자
Classifier : 분류
regressor : 회귀

Supervised Learning : 지도학습
Unsupervised Learning : 비지도학습