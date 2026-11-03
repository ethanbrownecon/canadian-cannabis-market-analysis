# Canadian Cannabis Sales After Legalization

A province and year analysis of cannabis sales and related indicators, built for a data management and data science course at Berry College.

## Question

How have cannabis sales, and the economic, demographic, and public safety measures alongside them, differed across Canadian provinces since recreational legalization in 2018?

## Why it matters

Canada legalized nationally in 2018, so provincial data offers a view of how a newly legal market develops and how it varies with local conditions.

## Approach

The notebook cleans a panel dataset, standardizes field names and types, builds total and per capita sales measures, and plots sales and selected provincial indicators over time. Missing 2022 to 2024 tax rate and licensing fee values are carried forward from 2021 within province. Missing or zero police rates are replaced with each province's mean.

The analysis is descriptive. Pre and post comparisons may reflect other changes over time, and the data do not measure youth cannabis use directly.

## Data

The source file is not included because its original citation and redistribution terms were not available. To run the notebook, add a licensed copy at `data/cannabis_canada.csv` with the columns used in `analysis.ipynb`, and cite the original sources.

## Run

```bash
python -m pip install -r requirements.txt
jupyter lab analysis.ipynb
```
