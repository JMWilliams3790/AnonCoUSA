# AnonCoUSA
Helping Anon Co. expand United States workforce with a focus on inclusivity with data analysis and machine learning.

## Folders and files:

[`data`](data) - This folder contains all of the CSV files that contain the data for the analysis.

 - [`job_postings.csv`](data/job_postings.csv) - CSV containing Anon Co. job postings from 2019-2020.
 - [`msa_data.csv`](data/msa_data.csv) - CSV containing metropolitan location data.
 - [`national_data.csv`](data/national_data.csv) - CSV containing national employment data.
 - [`skill_data.csv`](data/skill_data.csv) - CSV containing BLS data on occupational skills.

[`Images`](Images) - This folder contains all of the charts that were created in HTML format.
 - [`AllPosPost.html`](Images/AllPosPost.html) - HTML plot of postings by job.
 - [`AllLocPost.html`](Images/AllLocPost.html) - HTML plot of postings by location.
 - [`100PosPost.html`](Images/100PosPost.html) - HTML plot of 50 or more postings per position per year.
 - [`100LocPost.html`](Images/100LocPost.html) - HTML plot of 50 or more postings per location per year.
 - [`Cluster.html`](Images/Cluster.html) - HTML plot of cluster results from k means.

[`Exploration-Analysis`](Exploration-Analysis) - This folder contains the jupyter notebook with the analysis.
 - [`AnonCoExplore.ipynb`](Exploration-Analysis/AnonCoExplore.ipynb) - Notebook containing the reading, cleaning, transforming, analyzing, and plotting of the data.


## Tools:
 - Pandas - Used to read CSV files as dataframes to easily manipulate and view data
 - Plotly - Used to create interactive visualizations of the data.
 - Seaborn - Used to help create original cluster plot.
 - Matplotlib - Used to plot clusters for first time.
 - scikit-learn - Used to import K Means, build machine learning pipeline, cluster data, and score clusters.

## Approach:
 - [`approach_assumptions_etc.docx`](approach_assumptions_etc.docx) - An explanation of my analysis, assumptions, modifications, and extensions.
