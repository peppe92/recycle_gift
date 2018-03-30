# recycle_gift
This project try to find the optimal way to recycle gift, in order to satisfy the constrains given by social interactions.
## HOW TO RUN
1. first run ' create_social_interactions.m' function which creates the network. This function depends on a parameter which is the number of nodes in the network. From each node start 0.8XN links (a bit less because self connection are eliminated).
2. If you like to print the graph run 'plot interactions'
3. Then, choose the algorithm for minimisation. The coursework asked to repeat the simulation 10 times, therefore: 'many_cga' 'bga' 'many_pso' and 'es1p1' contains 10 repetition of the same code to evaluate reliability. `cga' and `pso' do not repet the code. They are useful for testing.
### Improvements
Contains a version that effectivly deal with permutation problem. There is another Readme there.
Access the Overleaf link to know more
[Overleaf link](https://www.overleaf.com/read/wvdqhdxrfzfc)

### What the other files contains?
- 'make_presents.m' is the cost function
- 'neighbour.mat' contains the topology, it is produced in the step 1.
Other files are not important
- 'recycle_gift.mlx' do the exaustive search, if needed.
- 'tightfig.m' is the function that makes the figure cooler, it is invoked in 2.
- 'WattsStrogats' I have never used, it will create a different topology.

