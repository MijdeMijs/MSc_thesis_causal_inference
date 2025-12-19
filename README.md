# MSc thesis causal inference 🧪

This repo contains the code that I made for my MSc thesis 👨‍🎓

My MSc thesis was about introducing Structural Causal Modelling (SCM) to the ecological domain. I performed simulations that highlight several aspects of SCM and causal effect estimations. To keep it simple and understandable, all systems where simulated linearly. This allowed to analytically solve the expected (biased) effects (see thesis report and appendices) and to perform OLS estimations to empirically show this under the different situations. Per system, 1000 silulations and OLS estimations where performed per situation and Kernel Density Estimation was used to result in the density plots.   

The Jupyter Notebook `MSc_thesis_notebook.ipynb` contains four main sections:
  - 🐣 Simulation 1: A simple system that highlights confounder bias;
  - 🐥 Simulation 2: A slightly more complex system that differentiates between the direct and total causal effect; 
  - 🦅 Simulation 3: Shows several estimation approches of which SCM outperformes the others;
  - 📊 Simulation 4: Represents a simplified realisic ecological example used in the presentation. 

I hope this is informative and/or usefull in any way. Happy coding 👨‍💻 
