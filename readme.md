# Potts model and phase transitions

In this project, joint work with Dario Filatrella, we use stochastic simulation and sampling techniques to study numerically phase transitions of the Potts model in the thermodynamic limit. 

## Project structure

Our methods and findings are explained in detail in `report.ipynb`, along with relevant figures. In short, we used the Metorpolis-Hastings algorithm to sample from the Boltzmann distribution over the state space, the maximally entropic probability measure compatible with any known average energy value. We studied the behaviour of the model around criticality, and we found evidence of a continuous phase transition when $q \le 4$, and of a discontinuous one for $q > 4$.
