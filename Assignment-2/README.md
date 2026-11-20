



AI FOR BUSINESS/Assignment 2

## What the script does

`Assignment_2.py` teaches a computer to recognize handwritten digits (0–9).

It loads a built-in scikit-learn dataset of 1,797 small 8×8 images, prints a few
basic facts about the data (how many images, how many pixels each, the first
five labels), then splits the data into a training set (80%) and a test set
(20%). A logistic regression model learns from the training set, and the script
reports how accurate it is on the test set (~96–98%), plus one example
prediction.

Run it with:

```bash
uv run Assignment_2.py
```

```
Flutter.gitignore
uv init  
uv run main.py  
source .venv/bin/activate 
uv pip install jupyter ipykernel pandas matplotlib scikit-learn
jupyter nbconvert --to script *.ipynb
```