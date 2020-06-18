# CNN with MNIST Dataset using tf.keras Functional APIs

neural network 모델을 실제로 구현하는 부분을 tf.keras functional APIs 를 사용해서 해볼 것

다른 부분은 동일

## Limitation of Sequential API
* We can't make
    * Multi-input models
    * Multi-output models
    * Models with shared layers(the same layer called several times)
    * Models with non-sequential data flow (e.g., Residual connections)