# Linear programming 

Solution has operated in Deterministic domain where all the parameters are known. 

#### Optimal Raw material mix problem (kindly refer LP_optimizer.ipynb)
- What should be the mix for creating different items from the raw material which maximizes the profit? 

#### Network optimization problem (kindly refer network_optimization_LP_programming.ipynb)
- Which facility should be operating and how to allocate demands (from the customer/end-users) to these facilities in order to minimizes the overall cost?

####  Solution
Solving linear programming (where all the constraints and objective function is the Linear function of the decision variables and guaranteed optimal solution if exist) using python optimizer interface. This repo allows you to add multiple decision vars and constraints etc. in a very easy way.

For Non-linear programming models, kindly use Pyomo or pyOpt (as python optimizer interface) instead of PuLP used in this repo. 

#### Key Note:
Defining an optimization model would be a pain if you have thousands of variables and constraints. In this repo, you can find the solution for the same by defining and initializing decision variables and constraints using compact and more scalable way - 
- More compact representation : using dictionaries and list powered by python
- Scalable : loops to define n numbers of variables and constraints instead of specifying them one by one ✌️

