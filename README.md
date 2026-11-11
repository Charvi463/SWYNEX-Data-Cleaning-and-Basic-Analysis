# SWYNEX-Data-Cleaning-and-Basic-Analysis
Basic cleaning, quality checks and statistical analysis of GSE138260 gene expression data.
# Project overview 
Performed Basic cleaning, ran quality checks and did statistical analysis of GSE138260 gene expression data using Google Colab.
# Dataset source
NCBI GEO, GSE138260
# Organism
*Homo sapiens*
# Dataset size
36 samples, 947,672 probe measurements
# Tools used
Python, Pandas, NumPy, Matplotlib
# Methods
Metadata extraction, missing-value checks, duplicate checks, descriptive statistics, visualization
# Results and Findings
A total of 36 samples were analysed, consisting of 17 Alzheimer's disease (AD) samples and 19 healthy control samples.
No missing values were detected in the extracted sample metadata or expression matrix, also no duplicate probe identifiers were identified.
The expression matrix contained 947,672 probe measurements across 36 samples.
The overall mean expression values were approximately 5.1896 for AD samples and 5.1878 for healthy controls.
The boxplot and histogram were used to examine the distribution of expression measurements across samples.
The overall average expression measurements were similar between the two groups.

# Interpretation
The dataset showed complete measurements in the examined fields and no duplicate probe identifiers. The basic statistical analysis provided an overview of the expression-data distribution and sample characteristics. Further gene-level differential expression analysis would be required to identify specific genes associated with Alzheimer's disease.

# Files
1. Data_Cleaning_Analysis.ipynb - Google Colab notebook containing Python code, data loading, metadata extraction, cleaning checks, statistical analysis and visualizations.
2. sample_analysis_results.csv - Contains the combined sample metadata and calculated statistical measurements for each sample.
3. sample_summary.csv - Contains descriptive statistics such as mean, median, standard deviation, minimum and maximum expression values for each sample.


