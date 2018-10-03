# Small_hacks
Small hacks useful for the data scientist and geostatistician

- Description

This repository aims to give some piece of my code useful for the every day job of the data scientist/geostatistician. It will be completed as I find the use for new tools. As always - this is a draft and it surely can be improved so do not hesitate to point out problems and to contribute :)

- Cheat on the topo

this piece of code uses clustering of X,Y coordinates and the Z(elevation) coordinate for the training dataset, to approximate the Z of an incomplete dataset who would only have X,Y coordinates -this would be the test set.

Its strenght would be that finding the optimum number of clusters is automated and takes into account:

- the spatial distribution of X,Y coordinates
- A scoring which minimizes the standard deviation of elevations within clusters

The final script writes down the clusters assignation for the incomplete dataset. Jupyter Notebooks is used to ease the lecture of the script
  
