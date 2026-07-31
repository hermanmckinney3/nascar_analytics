# rajah_caruth_88_v_32
Comparing Rajah's Stats in the 88 (JRM) car and the 32 (Jordan Anderson)


# NASCAR O'Reilly Auto Parts Series (NOAPS) Analytics
## Project Overview
This repository contains data engineering, statistical analysis, and machine learning projects focused on the NASCAR O'Reilly Auto Parts Series (NOAPS).
The project combines multiple data sources to build driver-level datasets for data analysis, statistical testing, visualization, and predictive modeling.

---

## Current Areas of Work

- Racing-Reference web scraping
- LapRaptor Loop Data integration
- Data cleaning and validation
- Dataset merging using pandas
- Driver performance analysis *(coming soon)*
- Statistical testing *(coming soon)*
- Machine learning *(coming soon)*

---

## Data Sources

The repository currently uses data from:
- Racing-Reference (race information and race results)
- LapRaptor (Loop Data)

---

## Current Data Files

- `noaps_2026_loopdata.csv`
  - 2026 LapRaptor Loop Data

- `noaps_2026_rr_race_info.csv`
  - Racing-Reference race information

- `noaps_rajah_caruth_2026.csv`
  - Final merged dataset used for Rajah Caruth analysis

---

## Current Notebook

`noaps_rajah_data.ipynb`

### Current Workflow

Current workflow:

- Import Racing-Reference race results
- Import Racing-Reference race information
- Merge both Racing-Reference datasets
- Import LapRaptor Loop Data
- Filter to Rajah Caruth
- Merge both data sources into a single analysis dataset

---

## Visualizations *(Coming Soon)*

- Average Starting Position
- Average Finish Position
- Green Flag Passes

### Example Visualizations
*Insert visualization here.*


## Statistical Analysis *(Coming Soon)*

Planned statistical analysis includes:

- Independent t-tests
- Team comparisons
- Driver performance comparisons

### Example Output
*Insert output here.*


## Machine Learning *(In Progress)*

Planned prediction models include:

- Expected Finish Position
- Top-10 Probability
- Top-5 Probability
- Average Running Position
- Driver Rating Prediction

### Example Model Performance
ex..


## Tools Used

- Python
- pandas
- BeautifulSoup
- NumPy
- SciPy
- Matplotlib
- Plotly
- Jupyter Notebook

---

## Future Work

- Analyze additional drivers
- Build multi-driver datasets
- SQL integration
- Power BI dashboards
- Machine learning models
- Weekly race predictions
- Full-season analytics

---

## Notes
- HTML race pages were collected locally for web scraping.
- LapRaptor Loop Data is merged with Racing-Reference data using `pandas.merge_asof()` to account for minor race date differences between the two data sources.
