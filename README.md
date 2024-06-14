# Matplotlib-Challenge
Overview
This project involves analyzing data from a pharmaceutical study. The study examines the effects of various drug regimens on tumor volume in mice. The main objective is to visualize and analyze the data using Python and Matplotlib, and to draw meaningful conclusions about the effectiveness of different treatments. I used chatgpt to debug some of my code and clean things up.

Repository Structure
The repository contains the following main components:

Analysis Folder: Contains the Jupyter Notebook with the analysis code.
Data Folder: Contains the raw data files used for the analysis.
README.md: Project overview and instructions.
Files
Analysis/pymaceuticals.ipynb: Jupyter Notebook containing the data analysis and visualizations.
Data/Mouse_metadata.csv: Metadata about the mice used in the study.
Data/Study_results.csv: Results of the study, including tumor volumes and timepoints.
Installation and Setup
To get started with this project, follow these steps:

Clone the Repository:

Open your terminal and clone the repository to your local machine:

sh
Copy code
git clone https://github.com/yourusername/Matplotlib-Challenge.git
cd Matplotlib-Challenge
Create the Required Folders and Add Data Files:

Create the Data folder and move the required data files:

sh
Copy code
mkdir Data
mv "path to/data/Mouse_metadata.csv" Data/
mv "path to/data/Study_results.csv" Data/
Install Dependencies:

Make sure you have the necessary Python libraries installed. You can install the required packages using pip:

sh
Copy code
pip install pandas matplotlib scipy jupyter
Open the Jupyter Notebook:

Navigate to the Analysis folder and open the Jupyter Notebook:

sh
Copy code
cd Analysis
jupyter notebook pymaceuticals.ipynb
Analysis
The Jupyter Notebook contains the following analysis:

Data Cleaning:

Combining data from different sources.
Handling missing values and duplicates.
Exploratory Data Analysis (EDA):

Summary statistics.
Distribution plots.
Comparative Analysis:

Box plots to compare tumor volumes across different drug regimens.
Line plots to analyze tumor volume over time for individual mice.
Correlation and Regression Analysis:

Scatter plots to explore relationships between variables.
Linear regression to model the relationship between mouse weight and tumor volume.
Results
The results of the analysis are summarized in the Jupyter Notebook, including:

Visualizations comparing the effectiveness of different drug regimens.
Insights into the correlation between mouse weight and tumor volume.
Identification of potential outliers in the data.
Conclusion
This project demonstrates the use of Python and Matplotlib for data analysis and visualization in a pharmaceutical context. The analysis provides insights into the effectiveness of various treatments and highlights the importance of thorough data exploration and cleaning.

