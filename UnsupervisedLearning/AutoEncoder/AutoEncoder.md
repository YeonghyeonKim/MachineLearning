# AutoEncoder / 오토인코더
피처 추출의 한 유형으로, 피처 추출을 통해 원본 피처셋에서 새로운 피처 표현을 생성하는데 사용할 수 있다.  
새로운 피처 표현은 학습된 표현 (learned representation)이라고 하며 지도 학습 문제에서 예측 성능을 향상시키는데 사용된다.  
오토인코더는 표현 학습 (representation learning)을 하기 위해 피드포워드(feedforward)와 비순환 신경망(nonrecurrent neural network)를 사용한다.  

신경망의 각 계층은 원본 피처의 표현을 학습하고 이어지는 다음 계층은 이전 계층에 의해 학습된 표현을 기반으로 학습된다. 오토인코더는 계층적으로 단순한 표현에서 점점 더 복잡한 표현을 학습하면서 점점 더 추상적인 개념 층을 학습한다.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEzMTE2OTY2M119
-->