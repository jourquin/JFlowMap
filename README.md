# JFlowMap

## Introduction 

[FlowMap](http://www.visualisingdata.com/resources/jflowmap/) is a research prototype developed
at the University of Fribourg in which one experiment with  various visualization techniques for spatial
 interactions, i.e. interactions between pairs of geographic locations. These can be migrations, 
 movement of goods and people, network traffic, or any kind of entities "flowing" between locations. 

Spatial interactions are often represented as origin-destination data, meaning that only the origins, 
the destinations and the magnitudes of the flows are known, but not the exact flow routes.

The goal of the work is to develop a tool which would help to explore and analyze temporal changes 
in origin-destination data. 

The project is, however, non longer developed nor maintained. This repository is based on a fork
 of the original code, which was automatically exported from code.google.com/p/jflowmap. Only two things were modified :
 - A more recent version of Proguard is shipped, that handles Java 8 classes.
 - The whole stuff is embedded in an Eclipse project.
 
 ## Compilation 
 
 Launch the ant "build-dist-package" target to generate a distribution zip file. 
 

 