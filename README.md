## Note on Contributions

This repository was originally forked from [sdean-group/balloon-outreach](https://github.com/sdean-group/balloon-outreach).  
During my **Cornell summer research program**, I worked extensively with this environment in Google Colab, completing a wide range of simulations, exercises, and algorithmic experiments focused on **autonomous balloon navigation** and **control systems**.

### Summary of Contributions
- Conducted multiple simulation studies using **A\*** search, **PID**, and **Model Predictive Path Integral (MPPI)** control to optimize trajectory planning.  
- Developed and visualized balloon trajectories, comparing **noisy vs. noiseless** environments and analyzing flight accuracy.  
- Implemented an **enhanced wind field model** incorporating jet stream, Coriolis, and seasonal effects for more realistic dynamics.  
- Configured and tuned simulation parameters (e.g., `num_steps`, initial coordinates, altitude, resource levels) to model long-distance flights such as **Ithaca → Canada**.  
- Created map-based trajectory visualizations with **Cartopy**, custom gridlines, and environmental overlays.  
- Designed experiments for **“fly-as-far”** and **target-seeking** objectives, iterating on parameters like time step, horizon, and sample size.  
- Collected and analyzed **expert state–action pairs** using MPPI and tree search agents, plotted performance metrics, and validated control policy behavior.

### General Impact
Through this work, I strengthened my understanding of **control optimization, environmental simulation, and AI-based trajectory planning**, bridging theoretical knowledge with real-world modeling and visualization. These projects deepened my interest in combining **AI and environmental systems** for research and practical applications.


# Balloon Outreach Simulation

This repository contains a balloon simulation environment for testing navigation strategies.

## Running in Google Colab

To run the demo notebooks in Google Colab, follow these steps:

1. Open [Google Colab](https://colab.research.google.com)
2. Under **Open notebook** click on **Github >**
3. Locate the relevant demo notebook on the `main` branch
