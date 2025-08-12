\# Project Title

This project contains an implementation of proportional response dynamics in production economies. 

\## Description

The dynamic is implemented in Python using the Jupyter framework. To run it, download all the files here and run in Jupyter the file simulation-dynamic.ipynb.

You will be prompted to type a number from 0, 1, 2, 3. This tells the program what simulation to generate as follows:

\- 0 will generate a certain two-agent economy;

\- 1 will generate a market with 101 players read from the file called weighted-graph.csv and equal initial bids (i.e. b\_ij = 1/n for all i,j); 

\- 2 simulates a  star market with 4 players; 

\- 3 (or any larger integer) simulates a market with random number of players and random matrix and random initial bids

In all of these cases, the initial quantity of good i is initialized to x\_i(0) = 1; also the initial budget of each agent i is initialized to B\_i(0) = 1.

This is the source code used to generate the images in the associated paper "Tit-for-tat strategies drive growth and inequality inproduction economies" (https://royalsocietypublishing.org/doi/full/10.1098/rspa.2024.0533).






