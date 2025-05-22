🧠 Neural Network with Manual Configuration and Educational Tracing
This project implements a simple feedforward neural network built from scratch using Python. It is designed for educational purposes, with step-by-step tracing of both the forward pass and backward pass (backpropagation).

📌 Features
Custom network architecture: configure number of inputs, hidden layers, and outputs.

Manual weight and bias assignment for full control.

Detailed trace output for:

Forward pass: weighted sums and activations.

Backward pass: error signals and gradients.

Easily extendable and readable class-based code.

🏗️ Network Structure
You can define:

* Number of input neurons

* One or more hidden layers with arbitrary neurons

* Number of output neurons

* Manual weights and biases for all layers

🚀 Getting Started
Follow these steps to run and understand this neural network from scratch:

✅ Prerequisites
Python 3.6+ installed on your system

A terminal or command prompt

Basic understanding of neural networks (inputs, layers, activations)

📦 **Step 1: Download the Script**
Save the code file as neural_network.py.

You can either:

Copy and paste the code into a new file in your text editor

Or download it from a GitHub repository (if applicable)

🧠**Step 2: Understand the Network Configuration**
When you run the script, the program will interactively ask you:

* How many input neurons your network should have

* How many hidden layers and how many neurons per layer

* How many output neurons

* The weights for every connection between layers

💡 This manual setup is designed to help you understand exactly how each value influences the output.

⌨️**Step 3: Run the Script**
Open a terminal or command prompt and run:
python neural_network.py
You’ll be prompted to enter the architecture and weights like so:


Enter number of input neurons: 2
Enter number of hidden layers: 1
Enter number of neurons in hidden layer 1: 2
Enter number of output neurons: 1

Input Layer → Hidden Layer 1
Weight from Input 1 to Hidden1 Neuron 1: 0.5
Weight from Input 2 to Hidden1 Neuron 1: -0.6
...
Then, you'll enter the input values:

Enter input values (space-separated): 0.9 0.1

📊 **Step 4: View the Forward and Backward Pas**s
After entering the input and weights, the network will:

1.Perform a forward pass, calculating all activations with detailed explanations.

2.Perform a backward pass, calculating all gradients and deltas layer by layer.

This helps you trace how:

* Inputs are transformed into outputs

* Errors propagate backward through the network

* Gradients are computed for each weight

📜 **License**
This code is open for educational and research use. Feel free to adapt and extend it.
