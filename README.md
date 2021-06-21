# Ant Colony Optimization

# Set up JAVA environment in Linux
- Install Java development Kit
- Set up environment variables for Java [link](https://www.dev2qa.com/how-to-set-java-environment-viriable-java_home-classpath-path/)

# Run the code
- `cd src; javac Algorithm/*` First go to src folder, then javac (javac - Reads Java class and interface definitions and compiles them into bytecode and class files.) compile the code to class file.
- Then you can use `java Algorithm.MaxMin ../tsp-data/eil76.tsp.txt 76 _Demo`  to run that code.

In the above example:
- "../tsp-data/eil76.tsp.txt" specifies the tsp test case.
- 76 is the ant system size
- _Demo is the suffix for the log file

The example output:
```
Jun 21, 2021 8:11:46 AM Algorithm.MaxMin main
SEVERE: runtime: 1219515
```
You can also see the log in the "MMLog_Demo" file.
And you can see another output file "e1l76MM-bf.csv".

And the csv file format:
epoch,mm(GSL(Global Shortest Length, branchingFactor for the ant system)

For the branching factor, please refer to the thesis: Dekel_Viner_ant_colony_optimization_bachelor_thesis.pdf

# Walk through the code
tsp problem, 

## Log
## tsp
problem domain

## variables
mainly the AntSystemArgs

## Algorithm
Need to abstract from the problem domain.
But from what we can see, it still use some problem domain features in the
algorithm codes.

# References
[MinMax Ant Orignal Paper](https://www.cs.ubc.ca/~hoos/Publ/fgcs00.pdf)
