# Modified Z-Score

The Modified Z-Score is a statistical method used for identifying outliers or extreme values in a dataset. It is a variation of the standard Z-score, which measures how many standard deviations a data point is away from the mean of the dataset. The Modified Z-Score, however, takes into account the median and the median absolute deviation (MAD) instead of the mean and standard deviation, making it more robust to outliers.

The formula for calculating the Modified Z-Score of a data point x is given by:

Modified Z-Score=0.6745×x−MedianMADModified Z-Score=0.6745×MADx−Median​

Where:

* Median is the median of the dataset.
* MAD is the median absolute deviation, calculated as the median of the absolute differences between each data point and the median.

The constant value 0.6745 is used to make the Modified Z-Score comparable to the standard Z-Score. In a standard normal distribution (mean = 0, standard deviation = 1), approximately 0.6745 of the data lies within one standard deviation from the mean.

The interpretation of the Modified Z-Score is similar to that of the standard Z-Score:

* A Modified Z-Score close to 0 suggests that the data point is close to the median and doesn't deviate significantly.
* A positive Modified Z-Score indicates that the data point is larger than the median, while a negative score indicates that it's smaller.
* The farther the Modified Z-Score is from 0, the more extreme the value is relative to the rest of the data.

When using the Modified Z-Score for outlier detection, you can set a threshold value above which data points are considered outliers. The choice of threshold depends on the specific context of your analysis and the characteristics of your dataset. It's important to note that while the Modified Z-Score is more robust to outliers compared to the standard Z-Score, it still assumes that the data follows a distribution that is suitable for this kind of analysis.