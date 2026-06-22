# Multiple Linear Regression – Startup Profit Prediction

Predicting profit for 50 startups based on R&D spend, marketing, administration costs and location using Multiple Linear Regression.


## Dataset

- **50_Startups.csv** — 50 records with features: R&D Spend, Administration, Marketing Spend, State, and Profit (target)


## What I Did

- Encoded the categorical `State` column using label/one-hot encoding
- Split data into training and test sets (80/20)
- Trained a Multiple Linear Regression model using Scikit-learn
- Predicted profits on the test set and compared against actual values
- Analysed which features have the strongest impact on profit


## Key Finding

R&D Spend has the strongest positive correlation with profit — startups investing more in R&D consistently show higher returns regardless of location.


## Tech Stack

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook


## How to Run

```bash
git clone https://github.com/Ayush28042005/Multiple-linear-regression.git
cd Multiple-linear-regression
pip install pandas numpy matplotlib scikit-learn
jupyter notebook multiple-linear-regression.ipynb
```


## Author

Ayush Saini 






