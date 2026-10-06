# Rainfall Advisory Analysis

This project analyzes monthly rainfall data for Nairobi, Nakuru, Kisumu, Mombasa, and Machakos to support an NGO in providing evidence-based planting advice. The analysis cleans invalid Machakos rainfall values, uses NumPy to calculate rainfall statistics, identifies dry and wet periods, and recommends the strongest two-month planting window for each county.

## How to Run the Notebook

1. Clone or download this repository.
2. Install the required dependency using `pip install -r requirements.txt`.
3. Open `rainfall_analysis.ipynb` in VS Code or Jupyter Notebook.
4. Select a Python environment with NumPy installed.
5. Run all notebook cells from top to bottom.

## Planting Advisory

- Nairobi, Nakuru, Kisumu, and Mombasa have their strongest two-month rainfall window in April-May.
- Machakos has its strongest planting window in November-December and records six dry months with rainfall below 50 mm.
- Farmers should use these rainfall windows as planting guidance while noting that the missing April and September Machakos values were imputed using the rounded average of its valid rainfall readings.
