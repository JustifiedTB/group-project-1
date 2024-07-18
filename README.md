# Health, Happiness, and Prosperity

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data Sources](#data-sources)
4. [Technologies Used](#technologies-used)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Challenges and Solutions](#challenges-and-solutions)
8. [Analysis and Findings](#analysis-and-findings)
9. [Visualizations](#visualizations)
10. [Future Questions](#future-questions)
11. [Contributors](#contributors)

## Introduction
This project is our Group Project 1 for OSU Bootcamp. 

## Project Overview

- Explore various global country performance metrics and information.
- Examine multiple datasets by country to compare & contrast different aspects of well-being.
- Investigate specific factors of healthcare and how it impacts lives globally

### Questions

- Can this data be used to inform governmental policy? 
- Do assessments on a population survey-based dataset agree with expert surveys and empirical data? 
- Are there correlative relationships between health related statistics?
- Are there correlative relationships between health and happiness?


## Data Sources

1. 2023 Global Country Development & Prosperity Index
   - Source: https://www.kaggle.com/datasets/tarktunataalt/2023-global-country-development-and-prosperity-index
   - License: CC BY-SA 4.0 (Creative Commons Attribution-ShareAlike 4.0 International)
   - For license details: https://creativecommons.org/licenses/by-sa/4.0/

2. World Happiness Report 2023
   - Source: https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2023
   - License: CC0: Public Domain
   - For license details: https://creativecommons.org/publicdomain/zero/1.0/

3. Global Country Information Dataset 2023
   - Source: https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023
   - License: Creative Commons Attribution 4.0 International License
   - For license details: https://creativecommons.org/licenses/by/4.0/

4. Global Hospital Dataset
   - Source: https://www.kaggle.com/datasets/alitaqi000/world-hospital-rankings-2023
   - License: Open Data Commons Open Database License (ODbL) v1.0
   - For license details: https://opendatacommons.org/licenses/odbl/1-0/

Note: Users of this project are advised to refer to the original sources for the most up-to-date license information and to comply with the terms of each license when using or redistributing the data.

## Technologies Used
Most of the work was done with Jupyter Notebooks or Google Colab using Python with libraries: Pandas, Matplotlib,
Numpy, Scipy, and Seaborn. AI tools (Claude, ChatGPT, and Bootcamp Xpert Assistant) were used for troubleshooting
errors, data visualizations, and generating code snippets.  

## Challenges

- Examining Data Sources:
    - Surveys, Weighted Data
- Data Cleaning:
    - Missing Values
    - Each Country not in every dataset
    - Normalizing Values
    - "\xa0" - a non-breaking space in Unicode
- Data Integration:
    - Combining Datasets
- Visualization Complexity:
    - Exploring visualization techniques outside of class
    - Customizing for clarity

## Analysis and Findings

- Dataset Comparison:

We primarily compared two datasets: the World Happiness Report 2023 and the 2023 Global Country Development & Prosperity Index.
We evaluated selected countries to compare their rankings across these datasets, assessing consistency in how nations were rated.

- Health Metrics Deep Dive:

We focused on health-related columns from both primary datasets, noting that they were based on different underlying data.
To expand our analysis, we incorporated two additional datasets: the Global Country Information Dataset 2023 and the World Hospital Rankings 2023.

- Correlation Analysis:

Using all four datasets, we investigated potential correlations between various health statistics and the health indexes from our primary datasets.
We discovered significant correlations among several factors, including:

Infant Mortality Rate
Maternal Mortality Rate
Physicians per Thousand (Population)

- Broader Implications:

Our analysis revealed that these health-related factors not only correlated with each other but also showed strong correlations with:

Overall Happiness scores from the World Happiness Report
Overall Prosperity scores from the Global Country Development & Prosperity Index

## Visualizations
[Description and examples of key visualizations created during the project]

## Future Questions

Our analysis has opened up several avenues for future research and consideration:

- Policy Implementation:

How can governmental policymakers implement strategies to improve the quality of healthcare, specifically targeting factors like infant mortality, maternal mortality, and physician availability?
What are the most effective ways to translate these findings into actionable healthcare policies?

- Healthcare Professional Utilization:

How can healthcare policymakers and professionals best use this information to improve health outcomes in their countries or regions?
What specific interventions might be most effective based on these correlations?

- Broader Statistical Relationships:

How much more complexly intertwined are the statistics we worked with compared to other statistics we didn't use?
Are there other key factors we haven't considered that might significantly impact or be impacted by these health metrics?


- Validity of Indices for Policymaking:

Is the World Happiness Report a useful survey to inform policymaking? What are its strengths and limitations in this context?
Similarly, how valuable is the Prosperity Index as a tool for policymakers? What aspects of it are most relevant or actionable?


- Causality vs. Correlation:

While we've identified correlations, what further research is needed to establish causal relationships between these factors?
How might we design studies to more definitively link health outcomes with happiness and prosperity?


- Regional and Cultural Factors:

How do these relationships vary across different regions or cultures?
Are there specific cultural or socioeconomic factors that significantly influence these correlations?

## Setup and Installation

To run this project, you'll need Python and several libraries. Follow these steps to set up your environment:

1. Ensure you have Python 3.7+ installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory in your terminal.
4. Create a virtual environment (optional but recommended):
5. Install the required packages: pip install pandas matplotlib numpy scipy seaborn jupyter

## Usage

To explore our analysis:

1. Navigate to the project directory in your terminal.
2. Launch Jupyter Notebook:
3. Open the main analysis notebook: `main_analysis.ipynb`
4. Run the cells in order to reproduce our analysis and visualizations.

Note: Ensure you have the dataset files in the correct directory as specified in the notebook.

For Google Colab users:
1. Open Google Colab (colab.research.google.com)
2. File > Open Notebook > GitHub
3. Paste the URL of this repository and select the main notebook

Remember to adjust any file paths in the notebook if you're using Google Colab.

## Contributors

- Joe Kunesh - [JustifiedTB](https://github.com/JustifiedTB)
- Mike Leston - [piiop](https://github.com/piiop)
- Juhaina Alqabaie - [Jalqabaie](https://github.com/Jalqabaie)
