# qp
Data Analysis for Qualifying Paper

The folder QP_DataAnalysis contains the following R Notebooks:

- QPDataAnalysis: main notebook. Contains MDS and hierarchical clustering analyses of data. The final model uses 6 themes and 40 roots.
- QPDataAnalysis_allRoots: Contains same MDS and hierarchical clustering analyses of data for 6 themes, extended for all roots.
- AltMDSPlots: code for alternative ways of plotting MDS: interactive plots where roots' glosses can be read by hovering on them, and 3D plots. These were done for visualization/inspection purposes and are not included in the current version of the paper

For these notebooks to run, the parent folder needs to have another folder named "QP_Data" with the following files:

- disp_dataset.csv: main dataset
- roots_glosses: list of roots with their corresponding glosses (useful for creating interactive MDS plots)
- Tilbe_dimensions: dataset with semantic dimensions adapted from Tilbe (2012)