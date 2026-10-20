# Parental Relationships & Mental Health Analysis

An exploratory statistical analysis project using Add Health survey
data to investigate associations between young people's reported
relationships with their parents and selected mental health indicators.

The analysis was developed in R as part of a statistics course.
It focuses on data preparation, descriptive statistics, and
visualizing associations among survey variables.

## Research Question

Among survey participants approximately 16.5 to 21 years old,
is satisfaction with relationships with parents associated with
selected mental health indicators?

The analysis also explores whether reported feelings of being
loved and wanted provide additional context for these relationships.

## Tools & Technologies

- R
- ggplot2
- descr
- Data cleaning and recoding
- Frequency tables and descriptive statistics
- Data visualization
- Categorical data analysis

## Dataset & Variables

The project uses selected variables from the Add Health study
(National Longitudinal Study of Adolescent to Adult Health).

The analysis focuses on:

- `age1`: Participant age.
- `H1PF5`: Satisfaction with relationship with mother.
- `H1PF25`: Satisfaction with relationship with father.
- `H1PF36`: How loved and wanted a participant feels.
- `H1SU1`: Whether a participant reported considering suicide
  during the previous 12 months.

These are the variable names used in the original analysis.
Response codes and missing-value conventions must be interpreted
using the study's documentation.

The analysis selected older participants, using an age threshold
of approximately 16.5 years. The number of observations varies
depending on the variables included and the missing responses
excluded from each analysis.

## Project Workflow

### 1. Data Preparation

Created analysis subsets, filtered participants by age, and handled
missing responses and special survey codes.

### 2. Descriptive Statistics

Created frequency tables to examine the distribution of responses
to questions about parental relationships, feelings of being loved
and wanted, and reported suicidal thoughts.

### 3. Data Visualization

Used bar charts to summarize individual variables and compare
the proportion of participants reporting suicidal thoughts across
different parental relationship response categories.

### 4. Statistical Analysis

Developed hypotheses concerning the independence of parental
relationship responses and mental health indicators.

The original write-up identifies chi-square tests of independence
as a proposed statistical approach. Complete test statistics,
p-values, and validated inferential conclusions should be added
only after the tests have been implemented and verified.

## Exploratory Observations

The original analysis reported that:

- Most participants in the analyzed subsets expressed satisfaction
  with their relationships with their mothers and fathers.
- Most participants reported feeling loved and wanted.
- The observed proportion reporting suicidal thoughts varied
  across parental relationship satisfaction categories.

These are descriptive observations from the original project.
They do not establish a causal relationship or demonstrate
statistical significance.

## Limitations

- The analysis uses a restricted age range rather than the entire study.
- Missing responses and special survey codes affect sample sizes.
- The original data-cleaning and variable-recoding steps should be
  reviewed before treating the results as final.
- Observational survey data cannot establish causation.
- Findings may not generalize beyond the analyzed sample.

## Data Privacy & Access

The raw Add Health data are not included in this repository.

Access and redistribution requirements depend on the data version
and its applicable terms. Do not commit restricted survey data,
participant-level records, or other sensitive information to GitHub.

The repository should contain documented processing steps and
only appropriate, non-identifying aggregate outputs.

## Reproducibility

The analysis was developed in R using packages including `ggplot2`
and `descr`.

To reproduce the analysis, obtain authorized access to the dataset,
place it in the expected local data directory, and update the
original scripts to use relative paths.

Record the required package versions and document the variable
recoding rules before presenting the analysis as fully reproducible.
