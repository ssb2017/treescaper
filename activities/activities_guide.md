# TreeScaper Activities

## Part 1: Non-Linear Dimensionality Reduction

The [activity guide](https://github.com/ssb2017/treescaper/blob/master/activities/NLDR.pdf).

There is also an [appendix](https://github.com/ssb2017/treescaper/blob/master/docs/appendix_nldr.pdf) 
with more details on the methods (NLDR, intrinsic dimensionality, etc) if you are interested.

## Part 2: Community Detection Methods

The [activity guide](https://github.com/ssb2017/treescaper/blob/master/activities/NLDR.pdf).

There is also an [appendix](The [activity guide](https://github.com/ssb2017/treescaper/blob/master/docs/appendix_com_detection.pdf) 
with more details on the community detection methods if you are interested.

## Additional exercises

### Nakleh et al. Yeast Data Set

Try analyzing the [yeast data set](https://github.com/ssb2017/treescaper/blob/master/data/nakleh.nex)
presented in the [powerpoint](https://github.com/ssb2017/treescaper/blob/master/docs/treescaper_workshop_present.pdf).

This is 106 gene trees estaimted for 5 species of yeats.  The gene trees were estimated by
maximum parsimony. The trees are rooted and unweighted (ie no branch lengths).

I have a put the community detection output I obtained [here](https://github.com/ssb2017/treescaper/blob/master/activities/nakleh_output_files).

The results are summarized in the [powerpoint](https://github.com/ssb2017/treescaper/blob/master/docs/treescaper_workshop_present.pdf).

### Goldman et al. Yeast Data Set

This [dataset](https://github.com/ssb2017/treescaper/blob/master/data/goldman_yeast.nex)
is from a paper by Goldman et al ()  that exteneded the Nakleh et al. dataset.  This tree set has more species and more genes.
The trees are unrooted and weighted.

I analyzed this data set and found evidence of strongly supported conflicting signal
in the bipartition covariance network.  This conflicting signal involves a completely different set of taxa.
See if you can recreate my [results](https://github.com/ssb2017/treescaper/blob/master/activities/goldman_output_files).
