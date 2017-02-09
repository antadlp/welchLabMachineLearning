import numpy as np
import matplotlib

from p2 import *

x = np.array(([3,5], [5,1], [10,2]), dtype=float)
y = np.array(([75], [82], [93]), dtype=float)

x = x/np.amax(x, axis=0)
y = y/100 #Max test
NN = Neural_Network()
yHat = NN.forward(x)
print(yHat)


