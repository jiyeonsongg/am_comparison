# AlphaMissense and Clinical Comparison Study
## Description 

This project analyzes the relationship between missense variant effect predictors (VEPs) and biochemical/clinical data from early-onset familial Alzheimer’s disease (EOAD).

Presenilin (PSEN1, PSEN2) and APP gene mutations are major genetic links to EOAD, affecting γ-secretase activity and Aβ peptide production. Using data from in vitro Aβ assays and age of onset (AAO) in patients, this study examines how variant effect predictors correlate with these experimental and clinical outcomes.

The repository includes code for data analysis and visualization, such as bar plots, scatter plots, and heatmaps, to explore patterns between predictor scores, Aβ profiles, and clinical data.

## Contributions
- Jiyeon Song: jis049@ucsd.edu
- Joshua Pillai: jppillai@ucsd.edu
- Mentor: Professor Chengbiao Wu: chw049@health.ucsd.edu

## Project Contents
### Data
- raw_data: Provided from public tools and databases from in vitro γ-secretase assays and clinical patient data
- processed_data: Run the codes to extract datasets and figures to the processed_data folder

### Visualizations
- scatter plot:
- bar plot:
- heatmap:

### environment setup for data_extraction
Create a new virtual environment with the command prompt using<br>
`python -m am_comparison`

Once you have activated your environment, install all required packages using the following command: <br>
`pip install -r requirements.txt`

Deactivate the environment when all done: <br>
`deactivate`
