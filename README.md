# 20.440.-Final Project: Analyzing the skin transcriptome of Alopecia areata patients

**Authors**

Evan Holbrook

Valeria Marquez Pellegrin


**Project title:**

Analyzing the skin transcriptome of Alopecia areata patients pre- and post-treatment with ruxolitinib, a JAK inhibitor

**Overview:**

Alopecia areata is a significant cause of disability affecting individuals' quality of life worldwide, with currently no definitive cure. Recent advancements in treatment strategies, notably the use of JAK inhibitors like ruxolitinib, have demonstrated promising outcomes, showing over 90% efficacy in some alopecia areata patients. However, variability in treatment response remains a challenge, as some patients exhibit no response to the treatment. This suggests that they may be novel underlying biological pathways involved in the pathophysiology of alopecia areata that have not been previously explored.

This project aims to explore the skin transcriptome of alopecia areata patients treated with ruxolitinib to uncover the molecular mechanisms driving the therapeutic effects. Through a detailed analysis of gene expression data before and after treatment, we seek to identify novel biological pathways and potential biomarkers that could predict treatment response.  The analysis includes data normalization, statistical testing, and visualization of the results to uncover significant differences in gene expression profiles. Insights gained could lead to the development of more effective therapeutic strategies, potentially benefiting a broader spectrum of patients.

**Data**

The dataset used in this analysis is publicly available under GEO Accession GSE80342. The data was collected as part of a clinical trial evaluating the efficacy of ruxolitinib, detailed in Mackay-Wiggan & Jabbari et al., 2016. The study cohort consists of 12 patients with moderate-to-severe alopecia areata and 3 healthy controls. Microarray analyses were performed on scalp biopsies taken at baseline and again 12 weeks post-treatment with ruxolitinib, focusing on patients who showed at least 50% hair regrowth, as non-responder data post-12 weeks was not included.

**Project Structure**

* Data/: Contains raw microarray data files downloaded from GEO Accession GSE80342.

* Results/: Stores outputs from the analysis scripts, including:

	* Figures/: Contains all visual representations generated from the data (e.g., Volcano Plots, Heatmaps).
	* Dataframes/: Stores processed data files including results from statistical tests.

* Code/: This directory contains the main analysis script in Jupyter Notebook (.ipynb) format.


**Installation:**

To conduct the analyses detailed in this project, you will need to set up a Python environment capable of running Jupyter Notebooks. Below are detailed instructions for setting up your environment and installing the required packages.

* Seaborn (0.12.0): A data visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics.
* Pandas (1.4.3): Provides high-performance, easy-to-use data structures and data analysis tools.
* SciPy (1.9.1): A library used for scientific computing and technical computing.
* NumPy (1.24.1): The fundamental package for scientific computing with Python, including support for arrays, matrices, and high-level mathematical functions.
* Matplotlib (3.6.2): A comprehensive library for creating static, interactive, and animated visualizations in Python.
* itertools: A standard library module for creating iterators for efficient looping.
* tabulate (0.9.0): Simplifies the creation of formatted output tables from lists and arrays.
* adjustText (0.9.1): Provides automatic text positioning in matplotlib plots to minimize overlaps.
* BioMart (0.10.0): Enables complex queries against biological databases.
* io: Used for handling in-memory file-like objects.


**References:**

Jabbari, A., Cerise, J. E., Chen, J. C., Mackay-Wiggan, J., Duvic, M., Price, V., Hordinsky, M., Norris, D., Clynes, R., & Christiano, A. M. (2016). Molecular signatures define alopecia areata subtypes and transcriptional biomarkers. EBioMedicine, 7, 240–247. https://doi.org/10.1016/j.ebiom.2016.03.036 

Mackay-Wiggan, J., Jabbari, A., Nguyen, N., Cerise, J. E., Clark, C., Ulerio, G., Furniss, M., Vaughan, R., Christiano, A. M., & Clynes, R. (2016). Oral ruxolitinib induces hair regrowth in patients with moderate-to-severe alopecia areata. JCI Insight, 1(15).
