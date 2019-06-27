---
layout: page
title: Dissertation
permalink: /thesis
---

## Energy Efficiency in Machine Learning
# Approaches to Sustainable Data Stream Mining

---
**Abstract**    

Energy efficiency in machine learning explores how to build machine learning algorithms and models with low computational and power requirements.
Energy efficient and scalable algorithms are necessary to be able to be deployed on embedded systems and other resource constrained devices.
Although energy consumption is starting to gain interest in the field of machine learning, still the majority of solutions focus on obtaining the highest predictive accuracy, without considering energy consumption.

This thesis explores green machine learning, which builds on green computing and computer architecture to design sustainable and energy efficient machine learning algorithms.
In particular, the thesis investigates energy consumption for data stream mining algorithms.
While data stream mining algorithms are able to process potentially infinite streams of data without incurring in intensive computations, building energy efficient solutions for streams of data is key to move machine learning to battery constraint devices.

This thesis comprises four parts, in the form of six papers.
The main contribution of the thesis is the per-node adaptive growth method for Hoeffding trees. This method is able to reduce the energy consumption of Hoeffding trees by growing each branch of the tree independently and under different criteria.
In particular, the thesis first introduces the concept of measuring energy consumption for software applications, and in particular for machine learning algorithms.
Second, it evaluates the energy consumption patterns of Hoeffding trees, showing the key energy bottlenecks for that class of algorithms.
Third, it addresses those bottlenecks by presenting the *nmin adaptation* method for Hoeffding trees and ensembles of Hoeffding trees, outputting up to 40 percent of energy reductions compared to the originals solution.
The thesis is finalized by presenting the Green Very Fast Decision Tree algorithm. This algorithm is able to output higher accuracy than the latest Hoeffding tree extension, while reducing its energy consumption by more than 20 percent averaged in 12 publicly available datasets.
