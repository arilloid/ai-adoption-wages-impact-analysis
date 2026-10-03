# AI Adoption and Wage Trends in Canada (2012-2024)

An exploratory analysis of whether wage trends across Canada's major occupational groups are associated with AI adoption in the industries where those occupations are concentrated.

**Headline result:** no meaningful linear relationship was found between industry-level AI adoption and occupational wages. The analysis is descriptive, not causal.

## Data

| Dataset | Source | Coverage |
|---|---|---|
| Wages (low, median, high hourly wage by National Occupational Category (NOC)) | [Statistics Canada, 13 annual files]((https://open.canada.ca/data/en/dataset/adad580f-76b0-4502-bd05-20c125de9116)) | 2012-2024 |
| Use of advanced or emerging technologies, by industry and enterprise size | [Statistics Canada](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=2710036701) | 2017, 2019, 2022 |

## Notebooks

- **`datasets_cleaning_transformation.ipynb`**: combining and standardizing the raw files, narrowing the data to the national level and major industry sectors, converting annual wages to hourly, cleaning NOC codes, and handling missing values and data errors.
- **`wages_advanced_tech_analysis_revised.ipynb`**: AI adoption by sector, wage trends by occupational group, the NOC-to-NAICS mapping, visualizations and correlation analysis.


## Main limitations

- Only three AI survey years exist, therefore the results show association at a broad level, not cause and effect.
- Occupations were linked to industries using a custom mapping built for this analysis (a judgment-based approximation).

**See the notebooks for the complete methodology and caveats.**


## Authorship
> This analysis was completed as part of a group project for the Introduction to Data Science course at York University. This repository shares only the part of the analysis I authored, with the consent of my groupmates.
