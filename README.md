# qp
Data Analysis for Qualifying Paper

The folder QP_DataAnalysis contains the following R Notebooks:

- MDSSemDims: MDS Analysis of Tilbe's Semantic Variables
- NonMetricMDS: To be deleted
- QPDataAnalysis: first trial -> to find the proportion of speakers that found each root+theme/figure pair acceptable, I summed over each participant response for a given root+theme pair and divide that for the total number of participants. This turned out not to be the best option because for pairs in which some participant(s) had an NA response (didn't do that instance), the proportion of acceptability lowered (NAs were taken as 0)
- QPDataAnalysis_nonNA: second trial -> This is the current code. This code omits NAs when calculating the proportion of speakers that found each root+theme/figure pair acceptable. This analysis improved the variance accounted by the model by around 1.5%.

For these notebooks to run, the parent folder needs to have another folder named "QP_Data" with the following fies:

- disp_dataset.csv: main dataset
- roots_glosses: list of roots with their corresponding glosses (useful for creating interactive MDS plots)
- Tilbe_dimensions: dataset with semantic dimensions proposed by Tilbe in his QP