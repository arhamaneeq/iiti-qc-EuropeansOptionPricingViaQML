# European Options Pricing via Quantum Differential Machine Learning

This project replicates and extends the findings presented by T. Sakuma (2023), applying Quantum Machine Learning (QML) techniques to predict European call and put options prices.

## Key Principles

- `Black-Scholes`: A foundational mathematical model for pricing derivatives, used here to generate synthetic training data
- `European Options`: Financial contracts exercisable only at expiration, providing boundary conditions for the Black-Scholes partial differential equation.
- `Differential Machine Learning`: A machine learning framework where the loss function is defined in terms of both the model output and its derivatives, enhancing accuracy in learning dynamic systems.
- `Parameter Shift Rule`: A quantum computing technique enabling the exact evaluation of circuit gradients with respect to input parameters via controlled phase shifts.
- `Angle Embedding`: A method of encoding continuous classical data into quantum states by applying rotation gates.

## Features
 
- Synthetic data generation based on the Black-Scholes equation
- 2-qubit quantum neural network trained with angle-embedded input data and tunable weights
- Performance evaluation and analysis of the trained model

### Technologies Used
- `Pennylane` by Xanadu
- `ScipPy`
### Papers Referenced
- T Sakuma, *Quantum Differential Machine Learning*, 2023
- BN Huge & A Savine, *Differential Machine Learning*, 2020
- K Mitarai et al., *Quantum Circuit Learning*, 2019 
- M Schuld et al., *Evaluating Quantum Gradients on Quantum Hardware*, 2018
- F Vatan & C Williams, *Optimal Quantum Circuits for General Two Qubit Gates*, 2004
### Authored by
- `Arham Aneeq`, BTech MEMS, IIT Indore, 2028 Batch
- `Hrishabh Mittal`, BTech CSE, IIT Indore, 2028 Batch