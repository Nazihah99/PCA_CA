## Dataset
Given a dataset, “pollution.csv”, that was proposed in McDonald, G.C. and Schwing, R.C. (1973) 'Instabilities of regression estimates relating air pollution to mortality', Technometrics, vol.15, 463-482. It contains 16 attributes describing 60 different pollution scenarios. The attributes are the following:

*	PRECReal: Average annual precipitation in inches
*	JANTReal: Average January temperature in degrees F
*	JULTReal: Average July temperature in degrees F
*	OVR65Real: of 1960 SMSA population aged 65 or older
*	POPNReal: Average household size
*	EDUCReal: Median school years completed by those over 22
*	HOUSReal: of housing units which are sound and with all facilities
*	DENSReal: Population per sq. mile in urbanized areas, 1960
*	NONWReal: non-white population in urbanized areas, 1960
*	WWDRKReal: employed in white collar occupations
*	POORReal: of families with income less than $3000
*	HCReal: Relative hydrocarbon pollution potential
*	NOXReal: Same for nitric oxides
*	SO@Real: Same for sulphur dioxide
*	HUMIDReal: Annual average % relative humidity at 1pm
*	MORTReal: Total age-adjusted mortality rate per 100,000

## Methodology
Dimensionality Reduction using PCA
Principal Component Analysis (PCA) is utilized to reduce the dimensionality of the dataset, allowing for a more efficient and informative clustering process. The optimal number of principal components is determined using a scree plot, capturing a significant proportion of the total variance while minimizing error.

## Clustering Algorithms
Two clustering algorithms, K-means and K-medoids, are applied to both the original dataset and the reduced principal components. The Silhouette Score and Within-Cluster Sum of Squares (WCSS) are utilized to identify the optimal number of clusters (k) for each scenario.

## Results
The chosen clustering methodology, K-medoids with PCA, is presented as the preferred approach for investigating the correlation between air pollution and mortality. The advantages of this method over traditional regression analysis are emphasized, highlighting its ability to provide more dependable and comprehensible results.
