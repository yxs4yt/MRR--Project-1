# DS 4002 Project 1

## Overview
This project analyzes a dataset of data science job postings to examine the prevalence of artificial intelligence (AI)–related skills across roles. Using a reproducible R-based workflow, the project cleans job posting data, extracts and structures listed skills, and computes summary measures related to AI skill presence. The analysis is fully script-driven and can be reproduced from the provided dataset and code.

## Repository Contents
This repository contains the primary R Markdown analysis file, the input dataset, and all derived outputs generated during analysis. The structure is designed to separate raw data, processing code, and results to support clarity and reproducibility.

## 1. Software and Platform

### Software
- R
- RStudio
- R Markdown

### Required Packages / Libraries
- tidyverse
- knitr
- stringr (via tidyverse)
- dplyr (via tidyverse)
- tidyr (via tidyverse)

### Platform
- macOS  
(The analysis should also run on Windows or Linux systems with a standard R installation.)

## 2. Repository Structure
project-root/
├── data_science_job_posts_2025.csv
├── DS 4002 Project 1.Rmd
├── README.md
└── output/
└── (generated tables or figures, if rendered)


- `data_science_job_posts_2025.csv`: Original dataset containing job posting information.
- `DS 4002 Project 1.Rmd`: Primary analysis script written in R Markdown.
- `README.md`: Project documentation and reproduction instructions.
- `output/`: Directory for rendered outputs such as HTML reports or figures.

## 3. Instructions for Reproducing Results

1. Install R and RStudio on your machine if they are not already installed.
2. Clone or download this GitHub repository to your local machine.
3. Open RStudio and set the working directory to the project root folder.
4. Ensure the dataset file `data_science_job_posts_2025.csv` is located in the project root directory.
5. Install required packages by running:
   ```r
   install.packages("tidyverse")
6. Open the file `DS 4002 Project 1.Rmd` in RStudio.
7. Click **Knit** to render the document, or run all code chunks sequentially.
8. The script will:
   - Load the dataset
   - Clean and structure skill information
   - Extract up to three skills per job posting
   - Identify AI-related skills
   - Compute summary measures, including AI skill counts and ratios
9. The rendered output will display the results and can be regenerated at any time by re-running the R Markdown file.

