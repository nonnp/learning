# Gesture Classification

This notebook was created for a senior project of mechanical engineering student at Chulalongkorn University by adapting from 
[Gesture recognition tutorial](https://github.com/arduino/ArduinoTensorFlowLiteTutorials/) by Sandeep Mistry and Don Coleman.

The project is about creating a low-cost gesture classification system using [EMG](https://en.wikipedia.org/wiki/Electromyography).

The system comprise of handmade EMG detection device and Arduino Nano 33 BLE Sense as a computing unit.

The notebook contains the neural network creating and training process using Tensorflow, 
then the model is converted into Tensorflowlite model to implement on the Arduino.

## Tools included

1. [Tensorflow (keras)](https://www.tensorflow.org/api_docs/python/tf/keras) and [Tensorflowlite](https://www.tensorflow.org/lite/api_docs)
2. [SVM](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)

[Go to notebook](gesture_classification.ipynb)
