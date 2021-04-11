# Quantum Machine Learning: Variational classifier

This is a [Xanadu tutorial](https://pennylane.ai/qml/demos/tutorial_variational_classifier.html) for PennyLane's library wich has the purpose to implement a variational quantum classifier. Here I will train a quantum circuit with labelled data and then use it to classify new data following the mentioned tutorial.

This tutorial is made up of 2 parts

- [ ] Fitting the parity function:
    Here we have to fir a parity function that has the form 
    $$f : x\in \{0,1\} ^{\otimes n} \rightarrow y = \left\{\begin{array}{lll}
    1& \text{if uneven number of ones in } x\\
    0 &\text{otherwise}
    \end{array} \right.$$

    For this I will have to:
    - [ ] Create the quantum device and build up the circuit.
    - [ ] Define the Cost function. 
    - [ ] Optimice the classifier with the training data.
    - [ ] Then run and test the classifier.

- [ ] Iris Classification
    - [ ] Create the quantum device and build up the circuit.
    - [ ] Load the Iris data set. 
    - [ ] Optimice the classifier with the training data.
    - [ ] Then run and test the classifier.

