# RandomWalk
A simulation using numpy and random module


Using numpy.random module we can easily simulate the real life experiments .
In this repo simulation of a game is done

Player , initially , is at floor 0 of a very tall building . He rolls a die :

on upper face if 1 or 2 appears - goes down by a floor
if 3/4/5 appears - goes up by one floor
if 6 appears - he rolls the die again

What is the probability that after 100 steps he will reach 50th floor ?



Following are the two methods to solve given problem:
1) Analytically
2) Using Random Distribution  -- simulation


Here I am implementing second one . We simulate this experiment 10 times to get a probability distribution of outcomes of throwing the die


By counting the number of elements , in the "ends" list , that are greater than or equal to 60 we can calculate the chance

In this particular np.random.seed(246) the chances are 78.4%


Data Visualization -


Single Experiment-
![caption-alt-text](./RandomWalk/blob/master/plot.png)

Simulation -
![caption-alt-text](https://github.com/shivanshuman021/RandomWalk/blob/master/simulation_plot.png)
![caption-alt-text](https://github.com/shivanshuman021/RandomWalk/blob/master/simulation_plot_transpose.png)
