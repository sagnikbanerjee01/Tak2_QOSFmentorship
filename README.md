# Tak2_QOSFmentorship
This repo contains the solution for Tak2 of QOSF mentorship program. The task has been coded in pennylane framework. 
First, a randomly chosen set of parameters is optimized via gradient descent method, to find the optimial angles for achieving the desired state
The circuit consists only of CNOTs, RXs and RYs. 
I start from all parameters in parametric gates being equal to 0
I find the right set of parameters using gradient descent  
Simulations are done with sampling - i.e. a limited number of measurements per iteration and noise. 
Lastly, I compare the results for different numbers of measurements: 1, 10, 100, 1000 and so on. We observe that with increase in number of shots, the accuracy of our model increases, i.e. the error in results decreases.
