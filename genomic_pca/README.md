# PCA_genomic

- This is a simple Principal component analysis(PCA) application using the real data(genome among some people), and to investigate what information does the PCs capture.
- The data is come from [The International Genome Sample Resource](https://www.internationalgenome.org/).
- The data is centered but is not scaled.
- There are 995 observations, and for each observation, there are 10104 columns of data:
  - first 3 columns: unique identifier; gender and population
  - the 10101 columns are a subsample of nucleobases from the individual’s genome
- The data matrix X is defined as：
  - Xij = 0, if the i-th individual has column j’s mode nucleobase fortheir jth nucleobase,
  - Xij = 1, otherwise.

