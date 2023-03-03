# Qualtrics for Research Data Collection

  - ***Author:*** Nelson Roque, PhD
  - [nelson.roque@ucf.edu](nelson.roque@ucf.edu)
  - Director of the Context Lab at University of Central Florida

-----

## Background

A reproducibility crisis (Ioannidis, 2005; Open Science Collaboration, 2015) has emerged as a threat to the scientific
enterprise. Over the last decade I've engaged in learning opportunities to become proficient across topics including
data wrangling and modeling of text, image, video, and eye-tracking data, as well as more recently sensor data, and
look forward to training the next generation of scientists on code-based methods to apply in their research.

  - Ioannidis, John P A. 2005. “Why Most Published Research Findings Are False.” PLoS Medicine 2 (8): e124.doi:10.1371/journal.pmed.0020124.
  - Open Science Collaboration. 2015. “Estimating the Reproducibility of Psychological Science.” Science 349 (6251):aac4716–aac4716. doi:10.1126/science.aac4716.

## Workshop Format

Qualtrics is a tool frequently used for research data collection through surveys. This workshop will teach survey design tips for reproducible survey research; and data wrangling of Qualtricsdata – the process of cleaning and transforming raw data into data suitable for analysis.

  - ***Location***: Zoom, Friday, March 3, 2023 3 p.m. to 4 p.m.
  - ***Format***: Live, with recordings available for later viewing.
  - ***Register***: Registration open until March 3rd, 2023 - [click here to register](https://ucf.qualtrics.com/jfe/form/SV_0AL2md8bJpwxuBM)
  - ***Materials***: 
    - Data: see [`data`](data) folder of this repository.
      - Sample Survey: see [`https://ucf.qualtrics.com/jfe/form/SV_9RnmgYsz6coyhca?SOURCE=ucf_workshop_march2023`](https://ucf.qualtrics.com/jfe/form/SV_9RnmgYsz6coyhca?SOURCE=ucf_workshop_march2023)
    - Slides: see [`slides`](slides) folder of this repository.
    - Code: see [`scripts`](scripts) folder of this repository.
    - Sample Qualtrics Surveys: see [`sample_survey_exports`](sample_survey_exports) folder of this repository.

## Before the Workshop

  1. Install R
    - [Download R](https://cran.r-project.org/)
  2. Install RStudio
    - [Download RStudio](https://www.rstudio.com/products/rstudio/download/)
  3. Install packages for various analyses

    ```
    install.packages(c('tidyverse', 'devtools', 'readr', 'tidytext', 'textdata',
    'topicmodels', 'wordcloud', 'ggwordcloud', 'qualtRics'))
    ```

## Learning Objectives

  - Describe various principles, tools and techniques supportive of collecting data on Qualtrics.
  - Develop a code-only pipeline to allow reproducibility of data prep and analyses.

## Submit your questions

Do you have any questions about the workshop or related content? [Submit your questions here](mailto:nelson.roque@ucf.edu)
