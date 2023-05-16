# Credit Card Customer Segmentation

Model to help identify segments from credit card customer data. To employ PCA analysis and KNN modelling to group data and determine key factors that differentiate segments.

## Project Motivation

- Experiment with alternative clustering approach (see [here](https://towardsdatascience.com/customer-segmentation-with-python-implementing-stp-framework-part-3-e81a79181d07) for technique inspiration) whereby PCA applied to rows (not columns as in airline customer project) used to feature engineer and guide desctiptive analysis of subsequent clusters generated via K-means.

## Learning Points

- Row-wise PCA use cases as relates to clustering.
- Use of bivariate component analyses to determine factors most prominently differentiating segments.

## Project Breakdown

### Data cleaning
- Conducted analyses to understand the dataset and clean it, handling outliers, dropping redundant features and stanardising it in the process.
- Applied PCA to group rows and identify key groupings that could help guide segment identification.

### Modelling
Applied KNN clustering regression and analysed resulting feature space to discern descriptors for identified segments.

### Plotting 
Took bi-variate approach to plotting data in order to determine which two factors discriminated well between all the segments.
