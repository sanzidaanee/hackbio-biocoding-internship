# Task description

## Task Code 2.1: https://github.com/sanzidaanee/hackbio-biocoding-internship/blob/main/Stage2/Code/microbiology.ipynb

## Video link : https://www.linkedin.com/posts/kazadi-ngoie-45a5901b2_as-part-of-the-hackbio-internship-stage-2-activity-7299441053567213569-3kt4?utm_source=share&utm_medium=member_desktop&rcm=ACoAADGQN4YBzKeiDNJO02AzEWVe51O4XNO2ZKk


# Microbiology

Look at this dataset here.

This is the description of the dataset . [open in a new tab, not a file to be downloaded]

Plot all the growth curves of OD600 vs Time for the different Strains with the following instructions

For each strain, plot a growth curve of the the knock out (-) an knock in (+) strain overlaid on top of each other

Using your function from last stage, determine the time to reach the carrying capacity for each strain/mutant

Generate a scatter plot of the time it takes to reach carrying capacity for the knock out and the knock in strains

Generate a box plot of the time it takes to reach carrying capacity for the knock out and the knock in strains

Is there a statistical difference in the time it takes the knock out strains to reach their maximum carrying capacity compared to the knock in strains

What do you see? Explain your observations as comments in your code

# Growth Curve Analysis of Different Strains

This repository contains Python code for analyzing growth curve data of various strains. The project includes data loading, data transformation, visualization, and statistical testing to compare the carrying capacity times of knock-in and knock-out strains.

## Overview

The analysis involves:
- Loading a tab-separated values (TSV) file containing growth curve data.
- Reshaping the data for plotting using Pandas.
- Visualizing the growth curves with Seaborn and Matplotlib.
- Calculating the time to reach 95% of maximum OD600 (an indicator of carrying capacity) for each strain.
- Generating scatter and box plots to compare carrying capacity times.
- Performing an independent t-test to determine if there is a statistically significant difference between knock-in and knock-out strains.

## Repository Structure

```
├── README.md
├── analysis.ipynb          # Jupyter Notebook containing the full analysis
└── requirements.txt        # List of dependencies (if applicable)
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://https://github.com/kazadingoie/hackbio-biocoding-internship
   ```

2. **Install Dependencies:**

   If you are using `pip`, you can install the required packages by running:

   ```bash
   pip install -r requirements.txt
   ```

   The project requires:
   - pandas
   - matplotlib
   - seaborn
   - numpy
   - scipy

3. **Run the Analysis:**

   You can open the Jupyter Notebook (`analysis.ipynb`) in Google Colab or your local Jupyter environment to run and explore the analysis.

## Data Source

The data is read directly from a GitHub-hosted TSV file:
```
https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/mcgc.tsv
```

Ensure that the file exists at the specified URL. If the file location changes, update the `data_source` URL in the code accordingly.

## Code Overview

- **Data Loading:** The script reads the TSV file using Pandas with tab separation.
- **Data Reshaping:** The data is transformed from a wide to a long format using the `melt` function for easier plotting.
- **Visualization:** Growth curves, scatter plots, and box plots are generated using Seaborn and Matplotlib.
- **Statistical Testing:** An independent t-test is performed to compare the carrying capacity times of knock-in and knock-out strains.

## Observations

- The scatter and box plots help visualize the variation in carrying capacity times among different strains.
- The t-test indicates whether the observed differences are statistically significant.
- In the provided example, there was no significant difference in carrying capacity time between the knock-out and knock-in strains.
