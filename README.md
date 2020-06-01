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

-  Step 1: We will develop a surrogate model based on ML to map landscape model parameters (input) to ASCAT obervations (output)
-  Step 2: Based on this surrogate model, we can tweak the landscape model parameters to get a series of ASCAT obervations. Therefore we can study the sensitivity of ASCAT obervations to certain parameters in landscape model.
-  Step 3: Based on the surrogate model acquired in Step 1, and knowledge on sensitivity from Step 2, we can detect the anomalies in the landscape model.
-  Step 4: By using the LDAS-Monde assimilation system, we can directly assimilate ASCAT observations into Landscape model.
