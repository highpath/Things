# CNN with MNIST Dataset using tf.keras Sequential APIs

## NN Implementation Flow in TensorFlow

0. Import Libraries

1. Set hyper parameters - learning rate, training epochs, batch size, etc.
 
2. Make a data pipelining - use tf.data

: data set을 로드하고 data set에서 앞에서 설정한 batch size 만큼 data를 가져와서 뒤에서 만들 network에 공급해 주는 것

3. Build a neural network model - use tf.keras sequential APIs

4. Define a loss function - cross entropy

: output과 정답을 비교하는 것. classification 문제를 풀 거기 때문에 cross entropy 사용

5. Calculate a gradient - use tf.GradientTape

: loss값을 weight에 대해 미분해서 계산을 해야 학습을 할 수 있다.

6. Select an optimizer - Adam optimizer

: 그 gradient를 이용해서 weight을 update 하는 과정

7. Define a metric for model's performance - accuracy
: 중간중간에 얼마나 학습이 잘 되고 있나 확인, 학습 다 끝난 후에도 이 모델이 얼마나 잘 학습을 했는지 확인

8. (optional) Make a checkpoint for saving
매번 처음부터 학습할 필요 x, 한번 학습하면 inference 만 하면 된다.

9. Train and Validate a neural network model