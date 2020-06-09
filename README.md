# team-atlas

# Team Atlas backlog
Backlog and team information for Team Atlas. The backlog is kept in the [issues](https://github.com/NLeSC/team-atlas/issues) of this repo. Furher information on projects can be found in the [wiki](https://github.com/NLeSC/team-atlas/wiki).

For an overview of what we are doing this sprint(a 2 week period) see the [Sprint Board](https://github.com/NLeSC/team-atlas/projects/19)

The Project maps below serve as a high level overview of all the goals, deadlines, and stories (todo items) for a project. Click on each map for a large version, with clickable stories, goals, and elements.

### eEcolidar

### Phenology Generalization

* Generalization of eScience tools
* Notebooks for education
* Comparison between Dask and Spark
* Publish previous work 

### Ice Shelves

### Global Vegetation
The goal of this project is to use direct (backscatter) and indirect (slope and curvature) ASCAT observations to monitor the vegetation water processes and detect the anomalies.

According to the proposal and previous work from Manuel and Xu, we are going to achieve this by three steps:

-  Step 1: Develop a surrogate model based on ML to map land-surface model parameters (input) to ASCAT obervations (output).
-  Step 2: Study the sensitivity of ASCAT obervations to certain parameters in land-surface model. This will be done by adding very small perturbations from an assumed distribution to the model states, and quantify the sensitivity of the ML-derived model. This is to ensure that the surrogate model is robust.
-  Step 3: Data assimilation. Use the surrogate model as a measurement operator in an assimilation framework to assimilate the ASCAT observables into the land-surface model. An example of the assimilation framework is LDAS-Monde assimilation system, which only works for soil moisture. Current plan is open to other framework or implement their own assimilation system.
