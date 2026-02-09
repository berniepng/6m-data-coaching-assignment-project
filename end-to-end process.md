- Tools used (e.g. Python + Pandas / DuckDB / SQL).

- How you loaded the CSV (~1M+ rows).
- Key cleaning steps (missing values, standardising categories, parsing dates, handling salary formats).
- Important feature engineering (e.g. seniority, salary bands, demand metrics, skill tags).
- EDA highlights: key patterns or anomalies you discovered that shaped your dashboard design.


# Rough Notes
Bernie's dashboard
- used claude Sonnet 4.5 (free version) as a coding guide
- used shuf to get 50000 rows for sampling purposes
 ''' (head -n 1 input.csv && tail -n +2 input.csv | shuf -n 50000) > sample.csv '''
