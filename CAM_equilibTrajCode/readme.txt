This folder contains the processed data files and code to generate the anaylsis figures for the 200ns simulations of Calmodulin Variants

Data Folders
	energyData - the output of the nonbonded energies generated from VMD
	RMSD	- data generated on the RMSD of the variant CAM trajectories (trajRMSD) and pairwise RMSD from a sample of all trajectories used to generate variant clusters (clustRMSD)
	
Text Data Files
	camSimulationFeatures.txt - processed features generated from coordinates of variant output structures
	CAMclustStructFeatures_dihedral.txt - includes dihedral calucations of CAM variant structues
	allPCAcentroids.tab - centroids used to generate euclidian distances
	clusterRMSD.txt - pairwise distances between clusters identified in variant trajectories

R Scripts and Data Files
	analyzeCAM.Rmd - R Markdown file of all analysis scripts of processed CAM features from MD trajectories
	camFeatures.clust.RData - R dataframe of processed variant features
	clusterStatsSummary.Eng.RData - summary statisticss of trajectory energetic features
	clusterStatsSummary.str.RData - summary stastistics of trajectory structural features
	summarySE.R - script for function that calculates the summary statistics of an R dataframe