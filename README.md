# Software Developer Trends Analysis

This repository contains Python code for analyzing trends in software development based on Stack Overflow Developer Survey data from 2019 to 2023.

## Data Sources
- [Stack Overflow Developer Survey 2019](https://insights.stackoverflow.com/survey/2019)
- [Stack Overflow Developer Survey 2020](https://insights.stackoverflow.com/survey/2020)
- [Stack Overflow Developer Survey 2021](https://insights.stackoverflow.com/survey/2021)
- [Stack Overflow Developer Survey 2022](https://insights.stackoverflow.com/survey/2022)
- [Stack Overflow Developer Survey 2023](https://insights.stackoverflow.com/survey/2023)

## Questions Explored
1. **What is the top programming languages used in Spain over the past 5 years?**
2. **How has the education level of developers changed over the past 5 years?**
3. **What is the change in learning methods among developers over the past 3 years?**

## Prerequisites
- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- NumPy

## How to Use
1. Clone this repository to your local machine.
2. Download the survey data for each year from the provided links.
3. Update the file paths in the code to point to the correct survey data CSV files.
4. Open the Jupyter Notebook and run each cell sequentially.

## Data Cleaning
- Duplicates are removed from each dataset to ensure accuracy in analysis.

## Analysis Steps
1. **Extract Relevant Columns:** We extract columns related to education, programming languages, country, and learning methods.
2. **Fill Missing Values:** Null values in each dataset are filled with the mode of their respective columns.
3. **Top Languages in Spain:** The top programming languages used in Spain are analyzed and visualized for each year.
4. **Education Level Changes:** The change in the education level of developers over the past 5 years is explored and visualized.
5. **Learning Methods Trends:** Trends in learning methods among developers are analyzed and visualized over the past 3 years.

## Results
- Results for each question are displayed in tables and visualizations within the Jupyter Notebook.

## Visualizations
- Bar charts and pie charts are utilized for visualizing the top programming languages, education level changes, and learning methods trends.

## Conclusion
This analysis provides valuable insights into the evolving landscape of software development in Spain. The findings shed light on the most popular programming languages, changes in education levels, and the shifting preferences in learning methods among developers.

Feel free to explore the detailed code, visualizations, and findings in the Jupyter Notebook. For any questions or suggestions, please create an issue in this repository.

**Note:** The provided analysis focuses on high-level insights, and technical details are available in the Jupyter Notebook for those interested in a more in-depth exploration.
