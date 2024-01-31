# Structured Bird’s-Eye View Road Scene Understanding from Surround Video

The code will be released after the paper is published.

## Introduction
This paper proposes ORNE, an online road network estimation framework for structured BEV road scene understanding. Specifically, we propose a road network representation, i.e., representing the lane centerline as an ordered point set and the road network as a directed graph, accurately describing the lane centerline instances and lane topological relationships in complex scenes. Then, we propose an online road network estimation framework that takes on-board surround-view video as input and utilizes hierarchical query embedding to extract the BEV road network around the vehicle. Finally, we introduce a temporal aggregation module that alleviates the occlusion issue in road scenes and improves the accuracy of road network estimation by effectively utilizing any number of historical frame information.

![image](https://github.com/jiapeng345/ORNE/blob/main/images/Fig1.jpg)
The visualization results demonstrate that ORNE can online and accurately extract a BEV road network containing lane centerline instances and lane topological relationships around the vehicle in complex scenes.



