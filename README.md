# Udacity Data Review
For the Data Scientist course on Udacity, this is the 'Write a data science blog post' project. I'm using Car Fuel & Emissions data: https://www.kaggle.com/mrmorj/car-fuel-emissions.

**Note**: I'm currenctly stuck on the data analysis and would like some help from a Udacity mentor/reviewer. You can find the questions at the very end of the Jupyter Notebook. Thanks in advance.

## About the data
I was interested in the data, because of the ongoing discussion regarding global warming and the emission of greenhouse gasses. And after taking a closer look at the data, there were a few interesting topics that could be addressed using the data.

- There's tax band labels assigned to the different cars. I'm wondering if it's possible to model these tax band labels using the data.
- Since the years are specified, it would be interesting to see how the environmental impact of cars have evolved during those years.
- It would be interesting to see which companies are ahead of behind in regard on their emissions.

## Requirements:
- Python3, pip, and virtualenv
- Kaggle account: https://www.kaggle.com

## Install (first time setup)
1. Clone project from GitHub: https://github.com/Schayik/udacity-data-review.git
2. Download data from Kaggle: https://www.kaggle.com/mrmorj/car-fuel-emissions
3. Unzip file and add **data.csv** folder to project
4. Create virtual environment: `virtualenv venv`
5. Activate virtual environment: `./venv/Scripts/activate`
6. Install dependencies: `pip install -r requirements.txt`
7. Create Kernel: `python -m ipykernel install --user --name venv`
8. Open Jupyter Notebook: `jupyter notebook`
9. A page in your browser will open: http://localhost:8888/tree
10. Open data-review.ipynb` and set Kernel to **venv**
11. Set Kernel to **venv**: Kernel -> Change kernel -> venv

## Setup
1. Activate virtual environment: `./venv/Scripts/activate`
2. Open Jupyter Notebook: `jupyter notebook`