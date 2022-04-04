# venture_nn

This Jupyter Notebook is a neural network analyzing venture capital data

---

## Technologies

Project uses:

[Pandas](https://pandas.pydata.org/)

[pathlib](https://docs.python.org/3/library/pathlib.html)

[tensorflow](https://www.tensorflow.org/)

[sklearn](https://scikit-learn.org/stable/)


---

## Installation Guide

Run this program in Jupyter notebook and have a Pandas, Pathlib, Tensorflow and SKlearn installed. 



---

## Usage

Utilize Jupyter Labs to interact with the software program

!["Jupyter Labs Example"](https://miro.medium.com/max/955/1*mXGu0MeYgnUkyR9ybVlQpg.png)

**Key example code for Neural Network**
```
# Define the number of neurons in the output layer
number_output_neurons_A1 = 15

# Define the number of hidden nodes for the first hidden layer
hidden_nodes_layer1_A1 = (number_input_features + 1) // 2 

# Review the number of hidden nodes in the first layer
hidden_nodes_layer1_A1

# Create the Sequential model instance
nn_A1 = Sequential()

# First hidden layer
nn_A1.add(Dense(units=hidden_nodes_layer1, input_dim=number_input_features, activation="relu"))


# Output layer
nn_A1.add(Dense(units=1, activation="sigmoid"))


# Check the structure of the model
nn_A1.summary()
```

---

## Contributors

Hugo Kostelni

---

## License

Open Source
