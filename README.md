# Exploring the Impact of Emoji Usage on User Engagement in YouTube Comments

## Overview
This repository contains an independent academic research project examining how emoji usage in YouTube comments influences user engagement, measured through the number of likes received. The study analyzes large-scale comment data from a high-engagement YouTube video by MrBeast to understand how emojis function as emotional and communicative signals in digital environments.

## Research Objective
The primary objective of this study is to evaluate whether the presence and type of emojis in user comments are positively correlated with higher engagement levels, specifically comment likes. The research also seeks to identify which emojis are most strongly associated with favorable engagement outcomes.

## Research Questions
- Does the inclusion of emojis in YouTube comments increase the number of likes received?
- Are certain emojis more likely to generate higher engagement than others?
- How does sentiment expressed through emojis relate to user interaction patterns?

## Methodology
- **Data Source:** YouTube comments extracted from a MrBeast video using the YouTube Data API  
- **Sample Size:** 182,545 user comments  
- **Approach:** Quantitative, cross-sectional analysis  
- **Techniques Used:**
  - Emoji extraction and frequency analysis
  - Sentiment analysis (positive, negative, neutral)
  - Correlation analysis and hypothesis testing
  - Pearson correlation and p-value significance testing

## Key Analytical Components
- **Emoji Usage Patterns:** Analysis of 909 distinct emojis and their frequency of occurrence
- **Engagement Metrics:** Number of likes received per comment
- **Sentiment Analysis:** Classification of emojis and comments into positive, negative, and neutral sentiment categories
- **Statistical Significance:** Identification of emojis with statistically significant relationships to engagement metrics

## Key Findings
- Only 2 out of 909 emojis showed statistically significant positive correlations with comment likes:
  - Rolling on the Floor Laughing
  - Face with Tears of Joy
- Emojis associated with strong emotional expression were more likely to influence engagement
- The findings support a positive relationship between emoji usage and user interaction on YouTube

## Hypothesis Testing
- **Null Hypothesis (H₀):** The presence of emojis in YouTube comments is positively correlated with the number of likes those comments receive  
- **Result:** Accepted, based on statistically significant findings

## Tools & Technologies
- R
- YouTube Data API
- `tuber`, `dplyr`, `tidyr`, and emoji processing libraries
- CSV-based data analysis

## Files
- `Exploring_Emoji_Usage_YouTube_Engagement.pdf` – Final research paper  
- `Exploring_Emoji_Usage_YouTube_Engagement.docx` – Editable version  
- `emoji_data.csv` – Cleaned dataset used for analysis  
- `R_Code_Emoji_Analysis.R` – Data extraction and preprocessing script

## Ethical Considerations
All data collection adhered to YouTube’s API usage policies. User data was anonymized and analyzed in aggregate to ensure privacy and ethical compliance.

## Author
**Ishan Basak**  
MS Marketing (Social Media & Mobile Marketing)  
Pace University  
May 12, 2024

