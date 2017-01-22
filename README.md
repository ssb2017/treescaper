# TreeScaper

## Introduction

This workshop will teach students to use the software, [TreeScaper](https://github.com/whuang08/TreeScaper), to analyze sets of phylogenetic trees. TreeScaper provides a collection of visual and quantitative tools for exploring and characterizing the phylogenetic information contained in a tree set. These tools can be broadly categorized into three types: 

1. Utilities for calculating basic information about topologies and bipartitions

2. Visualization of treespace in 2- or 3-dimensional space through non-linear dimensionality reduction

3. Detection and delineation of distinct ‘communities’ of trees using a graph-theoretic approach known as community detection. 

We will explain the theory behind non-linear dimensionality reduction and community detection and how these methods can be used to discover structure in tree sets indicative of various evolutionary scenarios.  A typical analysis pipeline will be demonstrated on a simple simulated dataset and on an empirical data set.  Both data sets will demonstrate the detection of evolutionary phenomena of broad interest to phylogeneticists.  Students will also be encouraged to bring their own datasets and time during the workshop will be devoted to implementing the analysis pipeline demonstrated in class and discussing the structure in the data that was found.

## Download software

Download the binary zip file appropriate for your OS (Mac, or Linux) here:

[TreeScaper](https://github.com/whuang08/TreeScaper/releases)

We will be using a pre-compiled version of TreeScaper with a graphical user interface (GUI), which requires no special installation steps. Just extract the zip and run the binary.  You may find the manual helpful as well.

*One important note*

The default security settings on current versions of Mac OS X do not allow users to open applications that have been downloaded outside the App Store with a simple double-click. Instead, you will need to hold down control and single-click on the TreeScaper app, then select “Open”. When asked if you are sure, select “Open” again.

## Activities

See the [activities guide](https://github.com/ssb2017/treescaper/blob/master/activities/activities_guide.md).

## Call for Tree Sets

TreeScaper is particularly useful in identifying distinct clusters of trees within a tree set.  This structure may be indicative of a host of evolutionary phenomena, such as:

+ Recombination
+ Horizontal Gene Transfer
+ Hybridization
+ Incomplete Lineage Sorting
+ Migration

It may also indicate stochastic and/or systematic error.  If you have tree sets for which you expect these type of phenomena, or that you would like to analyze in TreeScaper for any reason, you can email the tree set prior to the workshop to **jrash@ncsu.edu**.  Please supply the tree set as a nexus file with a TREES block and a translate command.  An example can be seen [here](https://github.com/ssb2017/treescaper/blob/master/data/1000bp1L.nex).

Since we have a small group, I should be able to work with each of you to ensure that your data can be analyzed during the workshop.

Pleases ensure that the tree set does not contain more than a few thousand trees.  Larger tree set will be too computationally intensive too analyze during the workshop. 

At the moment, TreeScaper cannot analyze trees with non-overlapping taxa.  Please make sure that every tree has the same set of taxa.  You should be able to prune your trees down so that this is the case.  If you are having trouble doing this, let me know and I have a script that will do this.  If you know of a tree-to-tree distance that can handle non-overlapping taxa, you can supply me with the distance matrix and we can use this for many of the analyses in TreeScaper.
