# machine learning in chemisrty workshop
This workshop is a set of slides and jupyter notebooks intended to give an overview of machine learning in chemistry to graduate students 
in chemical sciences, which was originally presented during a research trip to Ben Gurion University and the Hebrew University in Jerusalem in February 2019.
 
The nominal length of the workshop is 3 hours, including time to look at the notebooks,
which are written in python and depend on numpy, scipy and scikit-learn, with plotting in 
matplotlib.

This workshop was prepared by students/post-docs in Heather Kulik's [group](http://hjkgrp.mit.edu/) at MIT, mainly [JP Janet](jpjanet.io) 
with assitance from Aditya Nandy (neural networks and notebooks) and Nick Yang (parts of the representation section) 

# Abstract
Machine learning techniques are having a tremendous impact on chemical sciences, providing accurate, low-cost alternatives to estimate potential energy surfaces and molecular properties, predict reaction outcomes and synthesis routes or suggest novel molecules with targeted properties. These new methods can potentially extend the size or number of systems that can be studied by an order of magnitude or more. 
In this workshop, we will provide a brief overview of the ingredients of machine learning models applied to chemical systems, 
with a focus on concepts that are transferable across different applications and colored with our experiences from working in 
the field.

We will begin by outlining the framework of supervised learning as applied to chemical systems,
and describe the types and amount of data that are commonly used for different applications and show how we can fairly
judge the performance of our models using the ideas of statistical learning theory.

Next, we will compare linear and nonlinear kernel models from a practical standpoint of both performance and
how these models relate to notions of chemical similarity. We will review different strategies used to convert
chemical systems to representations that preserve this chemical similarity, and feature selection methods that allow 
us to identify which parts of the representation are important. 

This will be followed by a discussion of the anatomy of neural networks, back propagation, (stochastic) gradient descent and a discussion of deep networks as automatic featurization.  
Finally, we will present some highlights from the literature that use the concepts from the workshop,
and show all of these parts in action with a simple kernel model demonstration written in python and applied 
to a common benchmark organic molecule data set. We will keep the presentation high-level and 
no detailed background is assumed, although we will use concepts from single-variable calculus and linear algebra. 
