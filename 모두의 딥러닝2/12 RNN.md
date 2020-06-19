# RNN

## Sequence data
* We don't understand one word only
* We understand based on the previous words + this word. (time series)
* NN/CNN cannot do this

시리즈 데이터.
이전의 결과가 그 다음에 영향을 미칠 수 있어야 함

## Recurrent Neural Network
x -> RNN -> y
usually want to predict a vector at some time steps.


We can process a sequence of vectors x by applying a recurrence formula at every time step:

Notice : the same function and the same set of parameters are used at every time step.

## (Vanilla) Recurrent Neural Network
The state consists of a single "hidden" vector h:

## Character-level language model example

## RNN applications
https://github.com/TensorFlowKR/awesome_tensorflow_implementations

* Language Modeling
* Speech Recognition
* Machine Translation
* Conversation Modeling/Question Answering
* Image/Video Captioning
* Image/Music/Dance Generation