 using setup.py we will be able to build our ML project as package. 
 
 if we want src folder to be found as package in setup.py create __init__.py

 whenever this command packages=find_packages() run in setup.py it will check how many folders contain __init__.py and will consider it as package, then it will build it, once it is build it can be imported like any other package eg seaborn or pandas. 

 