# dietary-supplement-use-analysis
Analysis of dietary supplement use patterns and safe-use awareness using open data.

Project Overview
This project aims to explore dietary supplement use patterns using an appropriate publicly available dataset. It focuses on describing observed patterns in supplement use and examining how they vary across user characteristics available in the selected dataset.

The project is being developed as a manageable, introductory data-analysis project using Python, descriptive statistics, and data visualisation. Machine learning and new survey collection are not required in the initial stage.
Research Question
What patterns can be observed between dietary supplement use and user characteristics in publicly available datasets?

The final scope will depend on the variables available in the selected dataset. If information about reasons for use, consultation with healthcare professionals, or safe-use awareness is not available, the analysis will be limited to the patterns the data can actually measure.

This project will not diagnose whether an individual medically needs a supplement.
Objectives
- Identify a suitable public dataset related to dietary supplement use.
- Review the dataset documentation, variables, study period, sample, and terms of use.
- Describe supplement-use patterns using frequencies, percentages, and appropriate summary statistics.
- Create clear visualisations to communicate the findings.
- Compare findings with relevant scientific literature where appropriate.
- Document limitations, including missing information and limits to generalisability.
Candidate Data Sources
The final dataset has not yet been selected. The following sources will be reviewed:
1. Kaggle – Dietary Supplement Use search
   https://www.kaggle.com/datasets?search=dietary+supplement+use
2. NHANES 2021–2023 – Dietary data
   https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Dietary&Cycle=2021-2023
The dataset will be selected only after its variables and documentation have been checked for relevance to the research question.
Planned Methodology
1. Search for candidate public datasets and review their documentation.
2. Select a dataset with variables relevant to the research question.
3. Import the data into Python.
4. Inspect variable definitions, missing values, duplicate records, and possible inconsistencies.
5. Document any data-cleaning decisions.
6. Calculate descriptive statistics, such as counts, percentages, and suitable summary measures.
7. Create a small set of clear charts based on the variables available.
8. Interpret the findings cautiously and describe the dataset's limitations.
9. Compare the results with verified scientific literature.
Planned Tools
- Python for data handling and analysis
- pandas for data preparation and summary tables
- matplotlib or seaborn for visualisation
- Jupyter Notebook for documenting the analysis
- GitHub for version control and project documentation
These tools are planned; implementation will proceed after the dataset has been selected.
Repository Structure
dietary-supplement-use-analysis/
├── README.md
├── references.md
├── data/
│   └── README.md
├── notebooks/
└── reports/
This structure is a proposed starting point and may be updated as the project develops. If a dataset's terms of use restrict redistribution, the raw data will not be committed to this repository; source and download instructions will be documented instead.
Current Status
Stage: Topic definition and preparation
- Project topic and preliminary research question defined.
- Candidate data sources identified.
- A GitHub repository created.
- Dataset selection, literature verification, and data analysis remain to be completed.
No analysis results are reported at this stage.
Next Steps
- Find and verify at least three relevant scientific publications, including DOI information where available.
- Review candidate datasets and their variable dictionaries.
- Select the dataset that best fits the research question.
- Update this README with the selected dataset, exact variables, and any changes to the research scope.
- Begin exploratory data inspection in Python.
Limitations
The scope and conclusions will depend on the selected dataset, its sample, the definitions used to measure supplement use, and the completeness of its variables. Observational data may show associations or patterns but cannot by itself establish causation. Results may not be generalisable beyond the population represented by the dataset.
References
A verified bibliography will be added to references.md after the literature search. Candidate datasets and sources will be documented once the final dataset is chosen.
