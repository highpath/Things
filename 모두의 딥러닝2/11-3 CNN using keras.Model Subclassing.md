# CNN with MNIST Dataset using tf.keras.Model Subclassing

## Model Subclassing
* Build a fully-customizable model by subclassing tf.keras.Model.

functional API를 사용하면 왠만한 복잡한 모델은 다 구현이 가능하지만, 서브클래싱을 사용하면 더 그 안에다가 더 개인적으로 추가하고 싶은 것들을 추가 가능

* Create layers in the __init__ method and set them as attributes of the class intaace.

* Define the forward pass in the call method.

