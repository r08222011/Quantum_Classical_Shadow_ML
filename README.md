# Classical Shadow Method Verification and Machine Learning of a Simulated Quantum System
This report will mainly discuss the paper [Provably efficient machine learning for quantum many-body problems](https://www.science.org/doi/10.1126/science.abk3333). In this paper, the author used a method called **Classical Shadow Representation**, which is the main work in another early paper [Predicting many properties of a quantum system from very few measurements](https://www.nature.com/articles/s41567-020-0932-7). We will show the performance of classical shadow representation, and also train a model which tries to learn to predict classical shadow representation of a given quantum system.

### Prerequisities
This code is mainly run with [pennylane](https://pennylane.ai) and [pytorch](https://pytorch.org)

### Get started
- `classical_shadow.py` contains the fundamental classical shadow represention method we need.
- `main_RandomComparison.py` will compare different configuration setup.
- `main_MachineLearning.py` will train the simulated quantum system generated by quantum circuits written with [pennylane](https://pennylane.ai) and [pytorch](https://pytorch.org).

### References
This project is mainly based on the results of 
- [Predicting many properties of a quantum system from very few measurements](https://www.nature.com/articles/s41567-020-0932-7)
- [Provably efficient machine learning for quantum many-body problems](https://www.science.org/doi/10.1126/science.abk3333). 

Detail of this project can be found in `report.pdf`