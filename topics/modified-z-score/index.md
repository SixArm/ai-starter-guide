# Modified Z-Score

The Modified Z-Score is a statistical method used for identifying outliers or extreme values in a dataset. It is a variation of the standard Z-score, which measures how many standard deviations a data point is away from the mean of the dataset. The Modified Z-Score, however, takes into account the median and the median absolute deviation (MAD) instead of the mean and standard deviation, making it more robust to outliers.

Formula:

* $\operatorname{Modified-Z-Score}=\frac{x−\operatorname{M}}{\operatorname{MAD}}×0.6745$
* $\operatorname{M}$ is the median of the dataset.
* $\operatorname{MAD}$ is the median absolute deviation, calculated as the median of the absolute differences between each data point and the median.
* $\mathrm{0.6745}$ makes the Modified Z-Score comparable to the standard Z-Score, because in a standard normal distribution (mean = 0, standard deviation = 1), approximately 0.6745 of the data lies within one standard deviation from the mean.

The interpretation of the Modified Z-Score is similar to that of the standard Z-Score: the farther the Modified Z-Score is from 0, the more extreme the value is relative to the rest of the data. When using the Modified Z-Score for outlier detection, you can set a threshold value above which data points are considered outliers. 