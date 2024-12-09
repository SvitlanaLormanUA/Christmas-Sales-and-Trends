# Christmas Movies Analysis

This repository contains a Jupyter Notebook for analyzing a dataset of Christmas movies. The notebook demonstrates how to:

- Download a dataset from Kaggle.
- Process and analyze the data using Python.
- Create visualizations and insights into Christmas movie trends.

---

## Requirements

To run the notebook, ensure the following are installed:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Libraries:
  - `pandas`
  - `json`
  - `kagglehub`
  - `IPython`

---

## Setup and Usage

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Install Dependencies

Use `pip` to install the required libraries:

```bash
pip install pandas kagglehub jupyter
```

### 3. Configure Kaggle API

Ensure you have a Kaggle API key. Place the `kaggle.json` file in the correct location (`~/.kaggle/` for most systems).

### 4. Run the Notebook

Start Jupyter Notebook or JupyterLab and open the file `Christmas-movies-analysis.ipynb`:

```bash
jupyter notebook
```
---

## Features

1. **Dataset Download**:
   - Automatically downloads the `christmas-movies` dataset from Kaggle using `kagglehub`.

2. **Data Processing**:
   - Cleans and processes the dataset for analysis.
   - Converts data into JSON format for visualization.

3. **Data Analysis**:
   - Analyzes key metrics such as IMDb ratings, runtime, and release years.

4. **Visualization**:
   - Interactive pivot tables created with Flexmonster.

---

## Dataset Details

- **Source**: Kaggle dataset `christmas-movies`
- **Columns**:
  - `title`: Movie title
  - `rating`: Content rating (e.g., PG, R)
  - `runtime`: Movie duration in minutes
  - `imdb_rating`: IMDb rating
  - `release_year`: Year the movie was released
  - Other fields related to genre, director, and stars.

---

## Flexmonster Integration

The notebook includes integration with Flexmonster to create interactive pivot tables:

- **Configuration**:
  - Rows: Movie titles
  - Measures: Average IMDb rating, Sum of release years
  - Grid Options: Totals and grand totals are disabled for a cleaner display.

---

## Notes

- Ensure the Kaggle API key is correctly set up for downloading datasets.
- The notebook is designed to be run in a Jupyter environment.
- Modify the Flexmonster configuration to suit your analysis needs.



