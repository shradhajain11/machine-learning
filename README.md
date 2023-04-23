# machine-learning
## Project Description

This project analyzes the NIFTY 50 companies in India by performing various calculations and creating new columns in the dataframe. The `nifty.csv` file is used as the dataset, which contains information on the companies' industry, market cap, current value, high and low 52-week values, book value, price-earnings ratio, dividend yield, return on capital employed, return on equity, and sales growth over the past three years.

After importing the necessary libraries and loading the dataset, the `Unnamed: 0` column is removed. Two new columns are created, `price_bookvalue` and `peg3`, which represent the price to book value ratio and the PEG ratio based on a 3-year sales growth rate, respectively.

## Libraries Used

- Pandas
- Numpy
- Matplotlib
- Seaborn

## File Descriptions

- `nifty.csv`: the main dataset used in this project
- `README.md`: this file
- `nifty.ipynb`: the Jupyter Notebook containing the code for this project

