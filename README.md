# Predictions for the 2024 Presential Elections Winner

## Overview
The study investigates the dynamics of voting behaviour of americans leveraging demographic, socioeconomic, and geographic factors, such as age, family income, education, state of residency, and sex. We use a Bayesian Logistic Regression model with Post-Stratification to predict the outcome between Biden and Trump with the mentioned factors as predictors. This research contributes to a better understanding of the factors influencing political engagement in American democracy by offering insightful information that might guide future electoral strategies and policy discussion.

To use this folder, click the green "Code" button", then "Download ZIP". Move the downloaded folder to where you want to work on your own computer, and then modify it to suit.

## Raw data
To obtain the raw data for this file, follow the instructions in data.txt in `data/raw_data`

## File Structure
The repo is structured as:

-   `data/raw_data` contains theinstructions to obtain the raw data.
-   `data/analysis_data` contains the cleaned dataset that was constructed.
-   `data/poststratified` contains different sets of poststratified datasets.
-   `model` contains fitted the model. 
-   `other` contains the sketches.
-   `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the R scripts used to simulate, clean, test and poststratify data.

## Statement on LLM usage
No LLMs were used for any aspect of this work.
