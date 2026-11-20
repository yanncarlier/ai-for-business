



AI FOR BUSINESS/Assignment 1

## What this script does

`Assignment_1.py` uses housing data from Taipei (`RealEstate.csv`) to predict
**house price per unit area**.

In plain terms, it:

1. Loads the data and shows the first few rows.
2. Draws a scatter plot of house age vs. price.
3. Trains a simple linear regression using **house age only**, then measures
   how wrong its predictions are (Mean Squared Error).
4. Trains a better regression using **several features** (age, distance to the
   nearest MRT station, number of nearby convenience stores, latitude and
   longitude), and shows how much the error drops.
5. Saves a bar chart comparing actual prices with predicted prices.

All results are printed to the terminal, and the three charts are saved as
`.png` files in the same folder.

Run it with:
```
Assignment_1.py
```

```
uv init  
uv run main.py  
source .venv/bin/activate 
uv pip install jupyter ipykernel pandas matplotlib scikit-learn
jupyter nbconvert --to script *.ipynb
```