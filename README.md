# PennyLane tutorials
This repository contains different tutorials that I have been following in order to learn how to use the Xanadu's Quantum Computing library called [PennyLane](https://pennylane.ai/). Here I am covering different tutorials of my personal interest, in particular those focused in Quantum Machine Learning tools.

## Quantum Variational classifier

This is a [Xanadu tutorial](https://pennylane.ai/qml/demos/tutorial_variational_classifier.html) for PennyLane's library wich has the purpose to implement a variational quantum classifier. Here I will train a quantum circuit with labelled data and then use it to classify new data following the mentioned. After that, it can be done a binary classification of data which can be graphed and shows the effectiveness of the classifier.

This tutorial is made up of 2 parts

- [x] Fitting the parity function
    For this I will have to:
    - [x] Create the quantum device and build up the circuit.
    - [x] Define the Cost function. 
    - [x] Optimice the classifier with the training data.
    - [x] Then run and test the classifier.

- [x] Iris Classification
    - [x] Create the quantum device and build up the circuit.
    - [x] Load the Iris data set. 
    - [x] Optimice the classifier with the training data.
    - [x] Then run and test the classifier.

## Variational Quantum Eigensolver

This is a method used to find the quantum states of a quantum system using variational methods. Such as those used in analytical mechanics when you are minimizing the variation of an action. In this case we are going to use this method to find the ground state energy of a molecule following the [tutorial](https://pennylane.ai/qml/demos/tutorial_vqe.html) offered by Xanadú using PennyLane.

* [x] Build the electronic Hamiltonian
    * [x] Specify the properties of the molecular state of interest; its geometry, charge and multiplicity.
    * [x] Give the basis set used to approximate the atomic orbitals.
    * [x] Compute the Hamiltonian of the molecule in the Pauli basis.
* [x] Implement the VQE algorithm
    * [x] Create the quantum device and build up the circuit.
    * [x] Define the cost function to be minimized.
    * [x] Run the algorithm and check that the ground state corresponds to the ground state of the molecule.