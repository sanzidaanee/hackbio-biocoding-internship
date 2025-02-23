# Biochemistry & Oncology: Analyzing Impact of Mutations on Protein Structure and Function
 @Slack, @Hana

This repository contains a Python notebook (`Biochemistry_task_(2_4).ipynb`) that analyzes the impact of amino acid mutations on protein structure and function, based on SIFT and FoldX scores.

### Link code: https://github.com/sanzidaanee/hackbio-biocoding-internship/blob/main/Stage2/Code/Biochemistry_task_(2_4).ipynb


## Task Description

### The task involved analyzing two datasets:

* **SIFT Dataset:** Contains scores representing the functional impact of mutations.
* **FoldX Dataset:** Contains scores representing the structural impact of mutations.

# Link dataset: 

The goal was to:

1.  **Data Preparation:**
    * Import both datasets.
    * Create a `specific_Protein_aa` column by concatenating the `Protein` and `Amino_acid` columns (e.g., "A5A607_E63D").
    * Merge the datasets based on the `specific_Protein_aa` column.
2.  **Identifying Deleterious Mutations:**
    * Identify mutations with a SIFT score below 0.05 (deleterious functional impact) and a FoldX score above 2 kCal/mol (deleterious structural impact).
3.  **Amino Acid Analysis:**
    * Extract the original amino acid from the `Amino_acid` column.
    * Determine the amino acid with the highest functional and structural impact.
    * Generate a frequency table of all amino acids.
    * Create a bar plot and pie chart visualizing the amino acid frequencies.
4.  **Interpretation:**
    * Briefly describe the amino acid with the highest impact.
    * Discuss the structural and functional properties of amino acids with more than 100 occurrences.

## Files

* `Biochemistry_task_(2_4).ipynb`: Jupyter Notebook containing the Python code for the analysis.
* `SIFT Dataset`:[Sift.tsv](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/sift.tsv)
* `FoldX Dataset`:[FoldX.tsv](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/foldX.tsv)

## Dependencies

The following Python libraries are required to run the notebook:

* `pandas`
* `matplotlib`
  

You can install these libraries using pip

## Results
The notebook provides:

* A merged dataframe with SIFT and FoldX scores.
* A list of mutations affecting both structure and function.
* Frequency tables and visualizations of amino acid occurrences.
* An analysis of the most impactful amino acids.

## Author

* Hana Nadir(@Hana) 

## Acknowledgements
* Galardini and colleagues for providing the research context.
* HackBio for the task.
