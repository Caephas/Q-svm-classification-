# Quantum SVM Classifier with Qiskit

## Overview

This project demonstrates the integration of quantum computing with classical machine learning techniques to enhance classification tasks. I utilize Qiskit's quantum computing capabilities to create quantum-enhanced feature maps and kernels, which are then applied to a Support Vector Machine (SVM) for binary classification. The example provided uses a synthetic dataset to simplify the understanding and implementation of quantum kernels in machine learning workflows.

## Features

- **Quantum Feature Map**: Uses Qiskit's `ZZFeatureMap` to encode classical data into quantum states.
- **Quantum Kernel**: Implements the `FidelityQuantumKernel` to compute the similarity matrix (kernel) between quantum states, which serves as input for the SVM.
- **Classification Task**: Applies a Support Vector Machine to classify data points from a synthetic dataset of concentric circles, demonstrating the potential of quantum computing in enhancing classical machine learning models.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8 or higher
- Qiskit
- Scikit-learn

## Installation

To set up your local environment to run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quantum-svm-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quantum-svm-project
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the Quantum SVM Classifier, execute the following command:
```bash
python quantum_svm.py
```

This will execute the script, which:
1. Generates and splits the dataset.
2. Normalizes the data.
3. Sets up the quantum feature map and kernel.
4. Computes the kernel matrices.
5. Trains the SVM.
6. Evaluates the classifier and prints the classification accuracy.

   - [Quantum SVM Classifier with Qiskit 🕵🏼](https://triangular-work-0e1.notion.site/Quantum-SVM-Classifier-with-Qiskit-a6ae8079ab2749238ca86532dddc49c8?pvs=4)
