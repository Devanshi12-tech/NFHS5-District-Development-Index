# NFHS-5 District Development Index — India

A district-level data analysis project using NFHS-5 data to construct and compare a composite development index across 707 Indian districts.

## Project Overview

The project combines district-level indicators into four development dimensions:

- Infrastructure
- Education & Gender
- Maternal Health
- Child Health

Each dimension is normalized to a comparable scale, and the four domain scores are combined using equal weights to calculate an Overall Development Score.

**Overall Development Score = (Infrastructure + Education & Gender + Maternal Health + Child Health) / 4**

Districts are then ranked according to the resulting score, followed by state-level and development-gap analysis.

## Key Findings

- 707 districts were included in the district-level analysis.
- Kerala ranks among the strongest-performing states in the constructed index, while Bihar is at the lower end of the state-level ranking.
- Maternal Health has the highest average district score (~0.73), followed by Infrastructure (~0.69).
- Education & Gender and Child Health have lower average scores (~0.62 each).
- Among the 20 lowest-ranked districts, Education & Gender is the weakest domain in 15 districts (75%), Maternal Health in 4 districts (20%), and Infrastructure in 1 district (5%).

## Analysis Performed

1. Data cleaning and preparation
2. Indicator normalization
3. Construction of four domain scores
4. Composite Overall Development Score calculation
5. District ranking
6. Top-20 and Bottom-20 district comparison
7. State-level development analysis
8. Development-gap analysis
9. Data visualization using Matplotlib

## Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab

## Repository Contents

- `README.md` — Project documentation
- `NFHS5_District_Development_Index.csv` — Final district-level dataset
- `NFHS5_District_Development_Index.ipynb` — Analysis notebook

## Dataset

The analysis is based on district-level data from the National Family Health Survey (NFHS-5).

## Note on Interpretation

The Development Index is a project-specific composite measure. Equal weighting is used across the four domains, and the results should be interpreted as comparative analytical findings rather than as an official government development ranking.
