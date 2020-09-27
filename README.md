# SDRE Simulator in Python



## Programming Platform:
* Python

## Used Libraries:
* NumPy 
* SciPy 
* Slycot 
* Control 
* Matplotlib

## Files included:
* Presentation Slide
* Published Paper
* Python Code



- This is just a one slide presentation that represents the SDRE algorithmic steps. Please run this in animation mode for better understanding 
- The attached IEEE paper named "Paper2_IEEE_NAPS_Kansas_US" presents one of the application of SDRE in wind energy. It contans the mathematical steps of the algorithm.  


## Description:

State Dependent Riccati Equation (SDRE) has become one of the most popular optimal control technique over the last few decade. This method, by allowing nonlinearities in the system states through state dependent coefficient (SDC) matrices and offering flexibility in designing these matrices, appeared to be a highly effective tool for the controller designing of strong nonlinear systems.

SDRE has been studied for both infinite and finite horizon case. In infinite horizon (IH) case, an algebraic Riccati equation with SDC matrices is solved online in order to find the control law. But in the finite horizon (FH) case, the solution is time dependent and a differential equation, rather than an algebraic equation, needs to be solved for finding the control law. FH-SDRE has been solved for both regulation and tracking, and applied in several complex nonlinear systems. To know more about this algorithm, please see the attached IEEE papers (especially, the second paper Paper2_IEEE_NAPS_Kansas_US).


In this work, instead of applying SDRE to any specific system, a general purpose simulator has been created in Python platform. Here, user only needs to input the system matrix (A), input matrix (B), desired state (Z), and the initial values, the program with calculate the output states, and the control signals. User also needs to tune the control parameter Q and R to get the desired output.




