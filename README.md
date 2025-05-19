
## Disney+ Hotstar Data Analysis

This project provides an exploratory data analysis (EDA) of a dataset containing information about movies and TV shows available on the Disney+ Hotstar platform. The aim is to clean, transform, and visualize the data to uncover interesting patterns and trends.

## Dataset

The dataset contains `9` columns and `9827` rows. It includes the following features:

- `Title`
- `Genre`
- `Release_Date`
- `Runtime`
- `Popularity`
- `Vote_Count`
- `Vote_Average`
- `Original_Language`


##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning Steps

- Converted `Release_Date` to year format
- Dropped irrelevant columns: `Overview`, `Original_Language`, `Poster_Url`
- Removed duplicate rows
- Cleaned and split `Genre` into individual categories
- Handled outliers in `Popularity` and categorized `Vote_Average`

## Key Insights

- Analysis of movie popularity over the years
- Most common genres and their average vote scores
- Relationship between popularity, vote count, and runtime
- Distribution of content release trends over time

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/disney-hotstar-analysis.git
   ```
2. Install required libraries (if using virtual env):
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open and run `Disney_Hotstar_Data_Analysis.ipynb` in Jupyter Notebook or any IDE that supports `.ipynb` files.

## Notes

- Dataset file: `mymoviedb.csv`
- The analysis focuses on univariate and bivariate insights for business and content strategies.

## Future Work

- Build a recommender system using collaborative filtering
- Add interactive dashboards using Plotly or Power BI
