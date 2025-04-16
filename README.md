# Accelerometer-Based-Patient-Movement-Monitoring-outside-Clinical-Settings


This repository contains the project materials for analyzing accelerometer data collected from stroke survivors. The project focuses on deriving a novel movement measure (M2) from raw accelerometer readings and comparing this measure with conventional therapist-assessed scores (MAL). The ultimate goal is to explore the utility and accuracy of accelerometer-based monitoring of patient movement outside of clinical settings.
Project Overview
Objectives

Data Processing:
    Read and preprocess accelerometer data stored for each patient, including handling data from separate patient folders.

Compute Movement Measure (M2):
    Derive M2 by calculating the mean acceleration magnitude after adjusting for gravity. This measure provides an objective metric derived from raw sensor signals.

Comparative Analysis:
    Compare the computed M2 values with therapist-assessed MAL (Motor Activity Log) scores using scatter plots and linear regression. This step evaluates the relationship and potential clinical relevance of the accelerometer-based measure.

Clinical Relevance:
    Discuss the advantages and limitations of accelerometer-based measurements relative to conventional assessments, thereby informing decision-making for remote patient monitoring.

Background

Conventional clinical assessments—like the Fugl-Meyer Assessment (FMA) and the Motor Activity Log (MAL)—have been the gold standard in clinical settings. However, accelerometers offer an opportunity to continuously monitor patient movement in daily environments. This project demonstrates how accelerometer data can be processed to produce clinically meaningful metrics (M2) and how these metrics correlate with established assessments.
Files in This Repository

Results.ipynb:
    The main Jupyter Notebook which contains all the analysis steps:

Loading patient data from a CSV file (patients.csv)

Reading and preprocessing individual accelerometer log files from patient-specific directories

Computing the M2 movement measure based on accelerometer values

Generating visualizations to compare M2 values with therapist-assessed MAL scores

Running linear regression analyses to assess the relationship between the computed measure and conventional scores

Aim.pptx:
    A PowerPoint presentation that outlines the assignment goals, background information, and evaluation criteria.
    ​

Sample Data Files:
    Due to file size constraints, only representative data files (such as a sample patients.csv and a few accelerometer log files) are included. These files illustrate the data structure and format used for analysis. Instructions are provided within the Notebook on how to update the file paths to your local data location.


Installation and Setup

    Clone the Repository:

        Clone the repository using Git (or GitHub Desktop) to work with a local copy.

        Example:
        git clone https://github.com/Hemanth-072/Accelerometer-Based-Patient-Movement-Monitoring-outside-Clinical-Settings.git

Install Dependencies:

 Ensure that Python 3 is installed.

Install the required Python libraries using pip (e.g., pandas, numpy, matplotlib, scipy, scikit-learn).
        (Instructions are provided in the Notebook comments.)

How to Run the Project

Jupyter Notebook:
    Open and execute the Results.ipynb Notebook to run the complete analysis. The Notebook contains cell-by-cell instructions that guide you through data loading, M2 calculation, visualization, and regression analysis.

Visualization and Analysis:
    The Notebook will:

 Print a preview of the loaded patient data.

Process each patient’s accelerometer data and compute corresponding M2 values.

Generate a scatter plot comparing MAL scores to computed M2 values, along with a linear regression line and relevant statistical outputs (such as the correlation coefficient and p-value).

Next Steps and Further Analysis

To extend the current analysis, consider implementing the following enhancements:

Signal Filtering:
    Apply a low-pass filter to smooth the accelerometer data before computing the acceleration magnitudes. This can improve the reliability of the M2 measure by reducing noise.

Feature Extraction:
    In addition to the basic M2 measure, extract additional features (e.g., variance, peak counts, or frequency-domain features) that could provide deeper insights into the movement patterns.

 Advanced Statistical Methods:
    Explore clustering techniques (such as k-means) to group patients based on movement patterns or perform time series decomposition to further analyze periodic trends in the data.

 Method Comparison:
    Develop additional visualizations (like Bland-Altman plots) to compare the accelerometer-based measures with conventional assessments, discussing the clinical pros and cons of each approach in your final report.

Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please fork the repository and submit a pull request with a detailed description of your changes.

Contact

For questions or further collaboration, please contact:

    Project Maintainer: [ Hemanth Sai kumar Gaddam ]

    Email: [hemanthsaikumar07gaddam@gmail.com]

    GitHub: Hemanth-072



