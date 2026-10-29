# Nepal Earthquake Severity Index — EDA

## Overview
An exploratory data analysis of Nepal's Earthquake Severity Index dataset 
to understand the distribution of earthquake risk across different regions 
and districts of Nepal, and the factors that contribute to severity.

## Dataset
- Source: Kaggle — Nepal Earthquake Severity Index
- 3,985 areas across Nepal
- 12 features including Region, District, Hazard Intensity, 
  Exposure, Poverty, Vulnerability, and Severity

## Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

## Key Findings
1. Earthquake severity in Nepal is heavily right skewed — the vast majority of areas have very low severity, with only a few concentrated areas facing extreme risk.

2. Central Nepal faces significantly higher earthquake risk than other regions, with Bhaktapur (1.01) and Kathmandu (0.95) having the highest mean severity scores
3. Districts like Gorkha and Sindhupalchok appear in the top 10 most severe districts, consistent with the 2015 earthquake epicenter location
4. Poverty and Vulnerability have a moderately strong positive relationship — poorer areas tend to be significantly more vulnerable to earthquake damage
5. Exposure is extremely low across all regions but concentrated in a few outlier areas, particularly in Central Nepal

## Files
- `nepal_earthquake.ipynb` — Main analysis notebook
- `data/nepal-earthquake-severity-index-latest.csv` — Dataset