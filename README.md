# Linear programming 

Solution has operated in Deterministic domain where all the parameters are known. 

#### Optimal Raw material mix problem
- What should be the mix for creating different items from the raw material which maximized the profit

####  Solution
Solving linear programming (where all the constraints and objective function is the Linear function of the decision variables and guaranteed optimal solution if exist) using python optimizer interface. This repo allows you to add multiple decision vars and constraints etc. in a very easy way.

For Non-linear programming models, kindly use Pyomo or pyOpt (as python optimizer interface) instead of PuLP used in this repo. 

#### Key Note:
Defining an optimization model would be a pain if you have thousands of variables and constraints. In this repo, you can find the solution for the same
- More compact representation using dictionaries and list powered by python
- Loops to define n numbers of variables and constraints instead of writing one by one :'( 
