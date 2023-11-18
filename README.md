# NCCU Quantum Hackathon

## Introduction
Welcome to the Classical-Quantum CNN Hybrid Model with modified ! 

### The Model Overview
The model flow and the result is as below. With four qubits, we build our Quantum filter by using **angle encoding(RZ, RY)** to transform data into quantum state. And then we use **one-to-one stabilizer** to reduce the error flip bits. After the quantum layer, an 2-d array will be sent into our traditional CNN model to train.
![image](flow.png)
![image](bear.jpg)

### Key Features:
- **Quantum Filter**: Quantum noise is rising from the indeterminate state, our model is expected to reduce this noise. 
- **CQCNN model**: We implement the CQCNN by applying Quantum filter as an componet of CNN. 
- **Hybrid Integration**: Seamlessly integrates quantum computations with classical processes.

### Hardware Requirements:
  - Colab with T4 GPU
### Package Requirements:
  - sklearn
  - torch
  - pennylane
  - os
  - other basic packages

### Reference
  - [QCCNN](https://link.springer.com/article/10.1007/s11433-021-1734-3)

### Representation
  - [PPT](https://docs.google.com/presentation/d/1B7CRn1KzKgC5VPQzsKdMDd0DnHgwh6irscyfhocrWBU/edit#slide=id.g260c71146d5_0_3861)