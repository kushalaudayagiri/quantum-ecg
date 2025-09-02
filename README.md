**Quantum ECG Classification Using QSVM and Classical SVM**

**Overview:**
This repository contains Python code to compare Quantum Support Vector Machines (QSVM) and Classical Support Vector Machines (SVM) for multi-class classification of simulated ECG signals. The project is part of the research titled:
“Qubits Meet Heartbeats: A Python Reality Check for Quantum ECG”
The research investigates the accuracy and limitations of quantum machine learning for arrhythmia detection using Python and Qiskit simulators.

**Features:**
Simulates ECG dataset with 4 arrhythmia classes (AFIB, GSVT, SB, SR) and 11 clinical features
Dimensionality reduction using PCA to match quantum circuit qubit constraints
Classical SVM and Quantum SVM (QSVM) implementations with RBF and quantum feature maps
Benchmarks accuracy and displays confusion matrices for both models
Plots performance comparison and gap analyses for clear visualization

**Requirements:**
Python 3.8 or higher
Qiskit, Qiskit Machine Learning
Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn

**Use the provided requirements.txt or install directly with:** bash
pip install qiskit qiskit-machine-learning scikit-learn pandas numpy matplotlib seaborn

**Usage:**
Run the provided Jupyter notebook or Python script
The main experiment runs with qubit configurations
Adjust dataset size or feature maps in the code as needed
Visualizations for accuracy and confusion matrices will be generated

