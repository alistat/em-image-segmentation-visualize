# EM Algorithm
EM algorithm implementation and application on image segmentation, visualizing the progress, focusing on performance and arithmetic stability.

A Python 2 notebook.

Requires numpy, pandas, matplotlib and PIL.

The application segments an image into colour clusters, displaying the develompent of the clusters over the iterations.

The sampled versions applies the algorithm on a simple random sample of the total dataset to drastically increase performance.
The results are compared, regarding the error score, to the case where the total dataset is used.
