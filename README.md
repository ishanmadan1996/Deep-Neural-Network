# Deep Neural Networks

Creating a neural network model using Google's tensorflow open source library, and then training it to perform multi-class classification on given dataset of Handsigns. The classifier has to identify the number(0,1,2,3,4,5) from a persons hand sign.


## Usage

Clone the repository:

```
git clone https://github.com/ishanmadan1996/Deep-Neural-Network.git
```

Install the pre-requisite libraries:

```
pip install requirements.txt
```

Run all scripts in an ipython shell or a jupyter notebook.
Execute the script below to create a deep neural network, train and test it.
```
Tensorflow_Main.py
```

The script given below contains helper funtion such as load_dataset, random_mini_batches, convert_to_one_hot, predict.
```
tf_utils.py
```

## Output
The output consists of the accuracy of the model, in correctly classifying the number displayed by the handsign, given in testing dataset. As we can see the testing accuracy is pretty impressive, which can be improved by taking more number by using regularization techniques to reduce the overfitting. We can also test the accuracy of the neural network by giving our own example as input.

```
Cost after epoch 0: 1.855702
Cost after epoch 100: 1.016458
Cost after epoch 200: 0.733102
Cost after epoch 300: 0.572940
Cost after epoch 400: 0.468774
Cost after epoch 500: 0.381021
Cost after epoch 600: 0.313822
Cost after epoch 700: 0.254158
Cost after epoch 800: 0.203829
Cost after epoch 900: 0.166421
Cost after epoch 1000: 0.141486
Cost after epoch 1100: 0.107580
Cost after epoch 1200: 0.086270
Cost after epoch 1300: 0.059371
Cost after epoch 1400: 0.052228

Parameters have been trained!
Train Accuracy: 0.999074
Test Accuracy: 0.716667


```

## Built With

* [Python](https://www.python.org/doc/) - The scripting language used
* [TensorFlow](https://www.tensorflow.org/get_started/) - Library used for building neural network

## Authors

* **Ishan Madan** - (https://github.com/ishanmadan1996)

## Acknowledgement

'''
Special thanks to Professor Andrew Ng.
'''

