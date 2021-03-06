# <p align=center>Linear programming </p>

Solution has operated in **deterministic domain** where all the parameters are known. 

#### Optimal raw material mix problem (Refer LP_optimizer.ipynb)
- What should be the mix for creating different items from the raw material which **maximizes the profit?** 

#### Network optimization problem (kindly refer network_optimization_LP_programming.ipynb)
- Which facility should be operating and how to allocate demands (from the customer/end-users) to these facilities in order to minimizes the overall cost?

####  Solution:
Solving linear programming (where all the constraints and objective functions are the Linear function of the decision variables and optimal solution is guaranteed, if exist) using python optimizer interface. This repo allows you to add multiple decision variables and constraints etc. in a easy way.

For Non-linear programming models, kindly use **Pyomo** or **pyOpt** (as python optimizer interface) instead of PuLP used in this repo. 

#### Key Note:
Defining an optimization model would be a pain if you have thousands of variables and constraints. In this repo, you can find the solution for the same by defining and initializing decision variables and constraints using **compact and more scalable** way - 
- More compact representation **:** using dictionaries and list powered by python 🤏
- Scalable **:** using loops to define n numbers of variables and constraints instead of specifying them one by one ✌️

