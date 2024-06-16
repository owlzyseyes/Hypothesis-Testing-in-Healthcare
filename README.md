# Hypothesis Testing in Healthcare

## Project Goals

The primary goals of this project are to identify the adverse reactions associated with the drug and assess whether these reactions, if present, occur in significant proportions. The dataset has been modified for this analysis, specifically highlighting the presence and absence of adverse effects (`adverse_effects`) and the count of adverse effects in a single individual (`num_effects`).

### Scenario 1: Proportion of Adverse Effects

Null Hypothesis (H0): The proportion of adverse effects is the same in the Drug group and the Placebo group.
Alternative Hypothesis (Ha): The proportion of adverse effects is different between the Drug group and the Placebo group.

### Scenario 2: Independence of Adverse Effects and Treatment Groups

Null Hypothesis (H0): The number of adverse effects is independent of the treatment group (Drug or Placebo).
Alternative Hypothesis (Ha): The number of adverse effects is dependent on the treatment group.

### Scenario 3: Difference in Ages Between Groups

Null Hypothesis (H0): There is no difference in the average age between the Drug group and the Placebo group.
Alternative Hypothesis (Ha): There is a difference in the average age between the Drug group and the Placebo group.

## Dataset Source

The dataset was sourced from [Hbiostat](https://hbiostat.org/data/) and is made available through the Vanderbilt University Department of Biostatistics.

## Project Structure

- `drug_safety.csv`: The main dataset file.
- `notebook.ipynb`: Jupyter Notebook containing the data analysis code.
- `safety.rda`: Original unmodified dataset.

## Data Modification

For the purpose of this project, the dataset has been modified to include additional information on adverse effects.

## Instructions

To reproduce the analysis or contribute to the project, follow the steps outlined in the Jupyter Notebook (`analysis.ipynb`). 

Feel free to explore the dataset and contribute to the enhancement of drug safety analysis.

## Acknowledgments

Special thanks to [Hbiostat](https://hbiostat.org/data/) and the Vanderbilt University Department of Biostatistics for providing the original dataset.