# Canadian Cannabis Market Analysis

A province-year exploratory analysis of Canadian cannabis sales and related
economic, demographic, and public-safety measures before and after recreational
cannabis legalization in 2018.

## Analysis

The notebook cleans a panel dataset, standardizes field names and types,
constructs total and per-capita cannabis-sales measures, and visualizes sales
and selected provincial indicators over time. Missing 2022–2024 tax-rate and
licensing-fee values are carried forward from 2021 within province; missing or
zero police rates are imputed using each province's mean.

These are descriptive comparisons, not causal estimates. The data do not
directly measure youth cannabis use, and pre/post differences may reflect
other changes over time.

## Data

The source CSV and course handouts are not included. The source folder did not
contain a complete data citation or redistribution terms, so users must
identify and cite the original sources and verify their terms before using or
sharing a dataset. To run the notebook, place an appropriately licensed file at
`data/cannabis_canada.csv` using the columns in the original compiled dataset.

## Run the notebook

```bash
python -m pip install -r requirements.txt
jupyter lab analysis.ipynb
```

The notebook has no saved outputs because the underlying data is not
distributed with this repository.
