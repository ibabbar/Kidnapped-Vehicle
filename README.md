
# Kidnapped Vehicle Project
This project implements a 2 dimensional **Particle Filter** in C++ applied to a kidnapped vehicle. The kidnapped vehicle problem creates significant issues with the vehicle's localization system, and only a subset of localization algorithms can successfully deal with the uncertainty created; it is commonly used to test a vehicle's ability to recover from catastrophic localization failures.
The particle filter is given a map and some initial localization information (analogous to what a GPS would provide) map_data.txt in the data folder. The map_data.txt includes the position of landmarks (in meters) on an arbitrary Cartesian coordinate system. Each row has three columns

1. x position
2. y position
3. landmark id 


**Particle Filters** or Sequential Monte Carlo (SMC) methods are a set of genetic, Monte Carlo algorithms used to solve filtering problems arising in signal processing and Bayesian statistical inference. The filtering problem consists of estimating the internal states in dynamical systems when partial observations are made, and random perturbations are present in the sensors as well as in the dynamical system. The objective is to compute the posterior distributions of the states of some Markov process, given some noisy and partial observations. 


## Visualizing the Car's Localization based on Landmark Observations
The green lines are the car's observations of surrounding landmarks. I captured the screen as a gif animation to demonstrate the results. The particle filter completes the execution within the time of 100 seconds. The output says **"Success! Your particle filter passed!"** as the required criteria. 

![Image of kidnapped vehicle](images/kidnappedvehicle.gif)



## The contents of the repository

 - **src a directory with the project code:**

    **particle_filter.cpp** - Implements the particle filter methods
