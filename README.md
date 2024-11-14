# Childhood-Immunization-Coverage-in-Kenya
This repository contains files for Analysis of Childhood Immunization Coverage in Kenya, using the KDHS 2022 dataset. The data was collected, managed and published by the Kenya National Bureau of statistics (KNBS), which is the official Statistical Agency of the Kenyan Government mandated to collect, compile, publish and disseminate official statistics for public use. Child immunization is a highly cost-effective program which fosters health equity for the entire population. Kenya has made notable progress in expanding its immunization programs over the years, but disparities are still present in immunization coverage. These disparities are driven by socioeconomic, maternal, geographic, child, and place of birth factors.

# Study Objective

The main objective of this study was to assess the coverage of childhood immunization in Kenya among children aged 12 – 23 months based on socioeconomic, geographic, maternal, child, and place of birth characteristics.

## Key Processes
* **Data Preprocessing:** Cleaning and preparing the data by addressing data quality issues and transforming the data to make it ready for analysis.
* **Exploratory Data Analysis:** Generating various summary statistics and Visualizations to uncover patters in the data.
* **Modeling:** Building a Multiple Logistic Regression model to assess the relationship between Immunization Coverage and Geographic, Socioeconomic, Maternal, Child and Place of birth characteristics.

# Results

* Only 16.46% of the children were fully vaccinated i.e children who received all the doses of the vaccines. Also, only 19.52% of the children received full basic vaccination. That is, children who received 1 dose of BCG, 3 doses of Polio, 3 doses of DPT and 2 doses of Measles vaccines.
* Children born in richer families had 67% higher odds of full immunization compared to children born in poorest families. 
* Children born in richest households had 78% higher odds of full immunization compared to children born in poorest households.
*  The odds for children of mothers with primary education being fully immunized were 2.02 times the odds for children whose mothers had no education.
* The odds for children of mothers with secondary education being fully immunized were 1.95 times the odds for children whose mothers had no education.
* The odds for children of mothers with higher (college or university) education being fully immunized were 1.83 times the odds for children whose mothers had no education.
* Children of mothers aged 20-29 years had 68% higher odds of full immunization compared to children of mothers aged below 20 years. 
* Children of mothers aged 30 years and above had 89% higher odds of full immunization compared to children of mothers aged below 20 years. 
* Children who were sixth born or higher had 57.2% lower odds of full immunization compared to first-born children.
* Children in Garissa county had 88.42% lower odds of being fully immunized.
* Children in Mandera county had 84.71% lower odds of being fully immunized.
* Children in West Pokot county had 64.8% lower odds of being fully immunized.
* Children in Samburu county had 71.38% lower odds of being fully immunized. 
* Children in Narok county had 62.82% lower odds of being fully immunized.

# Tools and Libraries
RStudio Software. (tidyverse, haven, sjPlot, sjmisc, sjlabelled, gtsummary)

# Contributions
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.
