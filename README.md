# Christmas Sales and Trends Analysis
<img width="1548" alt="Screenshot 2024-12-15 at 20 16 34" src="https://github.com/user-attachments/assets/1f4dc19c-73c4-42d0-8816-79fbe7579d5a" />

This repository contains a Jupyter Lab and Flexmonster for analyzing a dataset of Christmas movies. The notebook demonstrates how to:

- Download a dataset from Kaggle.
- Process and analyze the data using Python.
- Create the pivot table with Flexmonster
- Create visualizations and insights into Christmas presents trends.

---

## Requirements

To run the notebook, ensure the following are installed:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Flexmonster CLI
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

Start Jupyter Notebook or JupyterLab and open the file `"Christmas-sales-and-trends.ipynb`:

```bash
jupyter notebook
```
---

## Features

1. **Dataset Download**:
   - Automatically downloads the `Christmas Sales and Trends` dataset from Kaggle using `kagglehub`.

2. **Data Processing**:
   - Cleans and processes the dataset for analysis.
   - Converts data into JSON format for visualization.

3. **Data Analysis**:
   - Analyzes key metrics such as IMDb ratings, runtime, and release years.

4. **Visualization**:
   - Interactive pivot tables created with Flexmonster.

---

## Dataset Details

- **Source**: Kaggle dataset `Christmas Sales and Trends`
- **Columns**:
The dataset contains the following columns:

1. `TransactionID`
2. `Date`
3. `Time`
4. `CustomerID`
5. `Age`
6. `Gender`
7. `Location`
8. `StoreID`
9. `OnlineOrderFlag`
10. `ProductID`
11. `ProductName`
12. `Category`
13. `Quantity`
14. `UnitPrice`
15. `TotalPrice`
16. `PaymentType`
17. `PromotionApplied`
18. `DiscountAmount`
19. `GiftWrap`
20. `ShippingMethod`
21. `DeliveryTime`
22. `Weather`
23. `Event`
24. `CustomerSatisfaction`
25. `ReturnFlag`

---

## Flexmonster Integration

The notebook includes integration with Flexmonster to create interactive pivot tables.

## Notes

- Ensure the Kaggle API key is correctly set up for downloading datasets.
- The notebook is designed to be run in a Jupyter environment.
- Modify the Flexmonster configuration to suit your analysis needs.



