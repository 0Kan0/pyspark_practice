# pyspark_practice
In this practices, we were proposed to carry oput 2 activities:

 - We were provided with a notebook with a centralised version of a sorting algorithm with logistic regression and we were asked to parallelise it.

 - From the parallelised implementation of the previous activity, we were asked to implement the Cross-Validation procedure on it, in which we have specified that we can only read the dataset from disk once.


## Dataset description
We were given a .csv data file called ‘botnet_tot_syn_l.csv’ separated by commas, consisting of 1000000 rows and 12 columns without header. These 12 columns are made up of floating values, with the exception of the last one, which is reserved for integer values of 0 or 1, thus representing a binary sort. Due to the large volume of data, a reduced version called ‘botnet_reduced_l.csv’ was chosen during development, which consists of only 400000 rows.
