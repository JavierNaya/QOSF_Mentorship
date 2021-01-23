This project was developed for the [Quantum Open Science Foundation](https://qosf.org/) mentorship program 
under the tutelage of Matthias Degroote.

The goal of this tutorial is to recreate the Zero Noise Extrapolation (ZNE) results from the article from 
[N. Klco et al., 2018](https://arxiv.org/abs/1803.03326). In which a VQE is used to find the gound state energy but 
then ZNE is performed.

We utilize qiskit as a backend to allow us to simulate noisy computers with the noise characteristics of their real devices. 
This tutorial can also serve as a generic guide for ZNE of VQE algorithms, requiring only simple modifications in the case of
4-dimensional hamiltonians.  	


Qiskit instalation guide: https://qiskit.org/documentation/install.html  \\
Mitiq instalation guide: https://mitiq.readthedocs.io/en/latest/README.html#installation
