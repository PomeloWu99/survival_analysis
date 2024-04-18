# Breast Cancer Treatment Outcome Analysis

## Introduction
This project focuses on analyzing the impact of hormone treatment on patients with node-positive breast cancer. Utilizing data from the German Breast Cancer Study Group collected between 1984-1989, we investigate whether receiving hormone treatment leads to a difference in recurrence-free survival (RFS) time compared to standard treatment.

## Dataset
The dataset comprises 686 observations and 12 variables, centering around the RFS time and treatment type received by the patients. A total of 440 patients received standard treatment, and 246 received hormone therapy.

## Methods
Our analysis includes:
- Exploratory Data Analysis: Assessing the balance of the cohort and understanding the distribution of the RFS time across different treatments.
- Statistical Analysis: Comparing the mean and standard deviations of RFS time between patients receiving standard vs. hormone therapy.
- Model Selection: Considering age as a potential confounder in the analysis due to its distribution across the cohort.

## Results
- The initial exploratory analysis indicates a balanced distribution of treatment types concerning recurrence status.
- The density distribution of RFS time suggests significant overlap between patients with and without recurrence/death across both treatment modalities.

## Limitations
The analysis acknowledges potential biases, particularly the age distribution's impact on RFS time, which has been retained in the final model.




