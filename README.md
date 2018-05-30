# Evolution-Cellular-Automaton
A very simplified version of evolution on a grid

In this simulation, there is a grid of "ecosystems" which is part of the "ecosphere."  
Each "ecosystem" is a grid, where rows are "organism" made up of a genotype
which is a list of integers (displayed as colors.)  The idea behind this one is that
the selection criteria for an organism to spread to another ecosystem is for it
to be different from all the other organisms in that ecosystem (it is "finding
its niche.")  So the organism who is least similar to the organism in another
ecosystem replaces the organism in that ecosystem which was the most similar
(crowded out by competitors.)
