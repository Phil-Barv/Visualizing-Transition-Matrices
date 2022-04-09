# Visualizing Transition Matrices

<br>

> A Markov Chain describes a sequence of states where the probability of transitioning from states depends only on the current state.
In this github repo, I create a transition matrix for a 5-node network system, show below, to model foot traffic in 3-hr time steps
beginning from an equally likelihood distribution v = (0.2, 0.2, 0.2, 0.2, 0.2). 

<br>

<p align="center">
  <img src="https://github.com/Phil-Barv/Visualizing-Transition-Matrices/blob/main/graph.png" alt="Five Node Network System" />
</p>


> The gif below shows the decay of the system to
the static distribution (0.15, 0.04, 0.26, 0.43, 0.12). The R code for simulating the Markov Chain and creating the visualizations 
is provided <a href="https://github.com/Phil-Barv/Visualizing-Transition-Matrices/blob/main/animate_transition.R">here in this repo</a>.

<br>

<p>
  <img src="https://github.com/Phil-Barv/Visualizing-Transition-Matrices/blob/main/animation.gif" alt="System Convergence Gif" />
</p>
