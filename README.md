# Differencial Privacy Experiments
This repository has the notebooks implemented while learning the concepts of Differential Privacy. It contents experiments, paper implementation and library testing 

# Dependencies
## Installation of special packages
```python
!pip install diffprivlib
```
## Libraries needed
`pandas==1.0.21`


# Implementation
The first notebook consists of 3 parts:
### 1. IBM diffprivlib library testing
It shows how the noise added through a differencial privacy package can affect the accuracy of the model.

### 2. Paper Implementation
It creates functions and the needed code to replicate the results shown in the paper (Lee-2011).
I implemented the laplacian noise mechanism and tested it over the sample data provided by the author, being able to replicate the results.

### 3. Synthetic data generation
It uses the functions developed for the paper implementation to create synthetic data based on the Iris dataset.


# Contact Information
Contact: gabriel.pilah@pucp.edu.pe
