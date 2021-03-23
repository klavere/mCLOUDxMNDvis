# mCLOUDxMNDvis

This repository includes Jupyter Notebooks for the visualization of extended Mobile Network Data from the [mFUND-Project xMND](https://www.bmvi.de/SharedDocs/DE/Artikel/DG/mfund-projekte/xmnd.html).

## Context
The notebooks were created as part of my Master's Thesis titled ["Visualizing Mobile Network Data - A User-Centred Design Approach Connecting Visual Analytics to Urban Public Transportation Planning"](https://cartographymaster.eu/wp-content/theses/2020_Klasen_Thesis.pdf).
The thesis was written within the joint [Master Programme on Cartography](https://cartographymaster.eu/) of TU Munich, TU Vienna, TU Dresden and Uni Twente and in coorporation with [Fraunhofer IAIS](https://www.iais.fraunhofer.de/).
For a quick impression, see the [Poster](https://cartographymaster.eu/wp-content/theses/2020_Klasen_Poster.pdf).

The notebooks are conceptualized for a specific analytic scenario in four stages. Each stage features a *spatial* and a *temporal* overview of the data. To get an overview over the concept and the different visualizations, check out slides 20 through 32 and 36 of the [thesis presentation](https://cartographymaster.eu/wp-content/theses/2020_Klasen_Presentation.pdf).

## Data and Functionality
To fully explore the notebooks, add a `/data` directory containing all datasets which can that can be downloaded from [mCLOUD](https://mcloud.de/web/guest/suche/-/results/detail/9A101FEC-3502-495A-9D93-BD8329A9D8AC).

Dataset | Notebooks, it is used in
------- | ------------------------
[celldf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/celldf.csv) | all stages - spatial overview
[flowdf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/flowdf.csv) | stage 1 - spatial overview
[cycledf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/cycledf.csv) | stage 1 - temporal overview
[anomFlowdf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/anomFlowdf.csv) | stage 2 - spatial overview
[anomCycledf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/anomCycledf.csv) | stage 2 - temporal overview
[cycleAndFlowODdf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/cycleAndFlowODdf.csv) | stage 3
[anomODdf.csv](https://www.mcloud.de/downloads/ingrid-group_ige-iplug-mcloud/9A101FEC-3502-495A-9D93-BD8329A9D8AC/anomODdf.csv) | stage 4

For the notebooks that feature maps (those with *_spatialOverview* in their name), you will need a **Mapbox access token**. Read how to create one [here](https://docs.mapbox.com/help/getting-started/access-tokens/). Then, in the respective notebooks, replace `MAPBOX_ACCESS_TOKEN` with your personal one.

The notebooks represent a prototype for an interactive visual exploration tool. At each individual stage, they are to be viewed side-by-side, e.g. using [JupyterLab](https://jupyter.org/).

![grafik](https://user-images.githubusercontent.com/49414732/112134617-380f1080-8bcd-11eb-9412-ede0c45f685a.png)
___
Author: Verena Klasen
