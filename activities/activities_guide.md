# TreeScaper Activities

## Part 1: Non-Linear Dimensionality Reduction

The [activity guide](https://github.com/ssb2017/treescaper/blob/master/activities/NLDR.pdf).

There is also an [appendix](https://github.com/ssb2017/treescaper/blob/master/docs/appendix_nldr.pdf).
with more details on the methods (NLDR, intrinsic dimensionality, etc) if you are interested. This appendix is from Wilgenbusch et al (2016).

## Part 2: Community Detection Methods

The [activity guide](https://github.com/ssb2017/treescaper/blob/master/activities/community_detection.pdf).

There is also an [appendix](https://github.com/ssb2017/treescaper/blob/master/docs/appendix_com_detection.pdf) 
with more details on the community detection methods if you are interested. 

## Additional exercises

### Nakleh et al. Yeast Data Set

Try analyzing the [yeast data set](https://github.com/ssb2017/treescaper/blob/master/data/nakleh.nex)
presented in the [powerpoint](https://github.com/ssb2017/treescaper/blob/master/docs/treescaper_workshop_powerpoint.pdf).

This is 106 gene trees estimated for 5 species of yeasts (Rokas et al, 2003).  The gene trees were estimated by
maximum parsimony. The trees are rooted and unweighted (ie no branch lengths).

I have a put the community detection output I obtained [here](https://github.com/ssb2017/treescaper/blob/master/data/nakleh_output_files).

The results are summarized in the [powerpoint](https://github.com/ssb2017/treescaper/blob/master/docs/treescaper_workshop_powerpoint.pdf).

### Goldman et al. Yeast Data Set

This [dataset](https://github.com/ssb2017/treescaper/blob/master/data/goldman_yeast.nex)
is from a paper by Goldman et al (2011)  that exteneded the Nakleh et al. dataset.  This tree set has more species and more genes.
The trees are unrooted and weighted.

I analyzed this data set and found evidence of strongly supported conflicting signal
in the bipartition covariance network.  This conflicting signal involves a completely different set of taxa.
See if you can recreate my [results](https://github.com/ssb2017/treescaper/blob/master/data/goldman_yeat_output_files).


# References

Wilgenbusch, James, Wen Huang, and Kyle Gallivan. 2016. “Visualizing Phylogenetic Tree Landscapes.”
BMC Bioinformatics.

Rokas A, Williams BL, King N, Carroll SB. Genome-scale approaches to resolving incongruence in molecular phylogenies. Nature. 2003 Oct 23;425(6960):798-804.

Hess, J., & Goldman, N. (2011). Addressing Inter-Gene Heterogeneity in Maximum Likelihood Phylogenomic Analysis: Yeasts Revisited. PLoS ONE, 6(8)

