# Simulation of 2-D Brownian Motion

This project simulates 2-dimensional [Brownian Motion](https://en.wikipedia.org/wiki/Brownian_motion) based on HTML5 and JavaScript. Use **hard sphere model**. Assume the interaction between two particles to be **perfect elastic collision**. 

In this project, you can

- **Visualize the motion** of all particles in the system. For example, how they scatter with each other, whether the trajectory of pollen particle looks random...
- **Visualize the velocity distribution** of all particles and check if it follows [Maxwell distribution](https://en.wikipedia.org/wiki/Maxwell%E2%80%93Boltzmann_distribution). 
- **Visualize** the distribution of **colliding points** on pollen particle. 
- **Change boundary condition** as you like (periodic or rigid). Periodic boundary can be used to simulate a system of infinite size. 
- **Change parameters** as you like, including number of particles, their radius and the initial velocity distribution (uniform or Gaussian). 
<br/>
![BM gif](https://github.com/Yangliu20/physics-simulation/blob/main/docs/images/BM_gif_1.gif)

## Usage

To begin, first install [**Chart.js**](https://www.chartjs.org/docs/latest/). 

Open the project in your browser (recommend: Chrome). Click `Start!` then the program will begin with default parameters showing in the parameter table. To change parameters, modify the table and click `Submit and Restart!`. After the simulation starts, you can click on `Show / Hide Trajectory` and `Periodic / Rigid Boundary` to adjust settings. Plots of velocity distribution and colliding points would update automatically. 
