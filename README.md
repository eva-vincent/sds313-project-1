# Super Bowl Ads Analysis (2000–2021)
## Overview
This project analyzes a dataset of 233 Super Bowl advertisements aired between 2000 and 2021 to determine the key drivers of commercial popularity. Using R, the analysis investigates the relationship between online view counts and creative elements such as celebrity cameos, animal features, and audience engagement metrics.

## Key Analyses
### 1. Engagement vs. Reach
Finding: There is a near-perfect positive linear correlation (r ≈ 1.0) between total interactions (likes, dislikes, comments) and view counts. High engagement is inextricably linked to high visibility, suggesting that "viral" mechanics are driven by active user participation rather than passive viewing.

### 2. The "Celebrity Premium" Myth
Finding: Contrary to popular belief, the inclusion of celebrities did not result in higher median view counts. In fact, ads without celebrities had a slightly higher median view count (approx. +9,000 views) than those with star power, indicating that celebrity presence alone guarantees neither popularity nor viral success.

### 3. The "Animal Factor"
Finding: Similar to the celebrity analysis, ads featuring animals did not outperform those without them. The median view count for non-animal ads was marginally higher (+1,470 views), suggesting that the "cute factor" is not a standalone driver of engagement.

## Tech Stack
Language: R

Libraries: ggplot2 (visualization), kableExtra (formatting)

Techniques: Correlation Analysis, Bivariate Analysis, Data Visualization
