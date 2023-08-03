# Code Reference for Numpy and Scipy
## Install Packages
```Bash
python pip install numpy scipy
```
## Include Packages
```Python
import numpy as np
import scipy as scp
```
## Array creation
```Python
np.array([1, 2, 3])              # array([1, 2, 3])
np.arange(start, stop, step)     # np.arange(5) -> array([0, 1, 2, 3, 4])
np.linspace(start, stop, n)      # np.linspace(0, 1, 5) -> array([0., 0.25, 0.5 , 0.75, 1.])

```
## Input and Output
```Python
np.loadtxt()
np.savetxt()
```
