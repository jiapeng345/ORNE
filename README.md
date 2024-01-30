# Structured Bird’s-Eye View Road Scene Understanding from Surround Video

The code will be released after the paper is published.

## Introduction
This paper proposes ORNE, an online road network estimation framework for structured BEV road scene understanding. Specifically, we propose a road network representation, \emph{i.e.}, representing the lane centerline as an ordered point set and the road network as a directed graph, which can accurately describe the structural information of road networks in complex scenes. Then, we propose an online road network estimation framework that takes on-board surround-view video as input and utilizes hierarchical query embedding to extract the BEV road network containing lane centerline instances and lane topological relationships in the 360° FOV around the vehicle. Finally, we propose a temporal aggregation module that alleviates the occlusion problem and improves the accuracy of road network estimation by considering any number of historical frame information. 

## Visualization results in complex scenes
The visualization results show that ORNE achieves impressive results in complex scenarios, proving the effectiveness of our proposed method.
### Part1: Visualization results under sunny and cloudy weather
![image](https://github.com/jiapeng789/SRSU/blob/main/assets/sunny_and_cloudy.jpg)

