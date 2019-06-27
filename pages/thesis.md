---
layout: page
title: Dissertation
permalink: /thesis
---

# Energy Efficiency in Machine Learning
## Approaches to Sustainable Data Stream Mining

---
### Abstract

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

---
This dissertation is a compilation thesis that consists of a number of published or publishable papers, synthesized into a thesis introduction.
The thesis author has been the main driver of all the publications. The author has planned the studies, designed the experiments, conducted the experiments, conducted the analysis and written the manuscripts.

---

### Tentatively included papers   
<br/>
* **García-Martín E.**, Rodrigues C., Riley G., \& Grahn H.  (2018)  *Estimation of Energy Consumption in Machine Learning*. Journal of Parallel and Distributed Computing, Special Issue on Advances on Parallel and High Performance Computing for AI. Elsevier *(Under review - Major revision)*

* **García-Martín E.**, Lavesson N., \& Grahn H. (2017).  *Energy Efficiency Analysis of the Very Fast Decision Tree algorithm*. In: Missaoui R., Abdessalem T., Latapy M. (eds) Trends in Social Network Analysis. Lecture Notes in Social Networks, (pp. 229-252), Springer. DOI: <https://doi.org/10.1007/978-3-319-53420-6_10> [PDF](http://bth.diva-portal.org/smash/get/diva2:1156925/FULLTEXT01.pdf)

* **García-Martín E.**, Lavesson N., \& Grahn H. (2017). *Identification of Energy Hotspots: A Case Study of the Very Fast Decision Tree*.  In: Au M., Castiglione A., Choo KK., Palmieri F., Li KC. (eds) Green, Pervasive, and Cloud Computing. GPC 2017. Lecture Notes in Computer Science, 10232, (pp. 267-281), Springer. DOI: <https://doi.org/10.1007/978-3-319-57186-7_21> [PDF](http://bth.diva-portal.org/smash/get/diva2:1156958/FULLTEXT01.pdf)


* **García-Martín E.**, Lavesson N., Grahn H., Casalicchio E., \& Boeva V. (2018)  *Energy-Aware Very Fast Decision Tree*. Journal of Data Science and Analytics, Springer.*(Under review - Minor revision)*

* **García-Martín E.**, Bifet A., Lavesson N., (2019) *Energy Efficient Ensembles of Hoeffding Trees*. Intelligent Data Analysis *(Under review)*.

* **García-Martín E.**, Bifet A., Lavesson N., (2019) *Green Accelerated Hoeffding Tree*. 2019 IEEE International Conference on Data Mining (ICDM). IEEE, 2019. *(Under review)*
