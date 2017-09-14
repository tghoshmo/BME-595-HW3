# BME 595 - Homework 3
## Tarutal Ghosh Mondal

* AND GATE
  * Hand crafted weights - [-30, 20, 20]
  * Weights obtained from trained neural network - [-14.07, 9.27, 9.27]
  
* OR GATE
  * Hand crafted weights - [-10, 20, 20]
  * Weights obtained from trained neural network - [-4.80, 10.53, 10.53]
  
* NOT GATE
  * Hand crafted weights - [10, -20]
  * Weights obtained from trained neural network - [6.02, -12.44] 
  
* XOR GATE
  * Hand crafted weights -
    * Layer[0] : [[-10, 20, 20], [30, -20, -20]]
    * Layer [1] : [-30, 20, 20]
  * Weights obtained from trained neural network - 
    * Layer[0] : [[-5.61, 11.37, 11.37],[17.92, 9.48, 9.48]]
    * Layer[1] : [-15.57, 10.23, 10.23]
    
# Comments
 * Hand crafted weights and the weights obtained from the trained network are not necessarilty identical. However they are more or less in the same proportion and produce similar results. 
 * Higher learning rate reduces the number of iterations required for convergence of gradient descent. However, too large learning rate will fail to converge. 
 * The optimum values of the weights could produce the target output values. 
  
