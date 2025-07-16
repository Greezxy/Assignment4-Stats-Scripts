# Assignment 4 – Python Statistics Walkthrough

This repository contains a Jupyter notebook that walks through basic statistical analysis and data visualization in Python. The notebook follows exercises from the *Statistics in Python* section of the SciPy Lecture Notes, authored by Gaël Varoquaux.

The goal of this assignment is to explore essential statistical methods using `pandas`, `matplotlib`, `seaborn`, and `statsmodels`, which are foundational tools for data science and biomedical data analysis.

## Source

Tutorial followed:  
https://scipy-lectures.org/packages/statistics/index.html  
Author: Gaël Varoquaux

## Contents

Assignment4-Stats-Scripts/
├── notebooks/
│ └── stats_python.ipynb # Notebook with completed exercises and commentary
├── environment.yml # Conda environment definition (Python 3.10, jupyterlab, etc.)
├── requirements.txt # (Optional) pip-based environment definition
├── .gitignore # Standard Python and Jupyter exclusions
└── README.md # This file

## Getting Started

### Clone the Repository
```
bash
git clone https://github.com/your-username/Assignment4-Stats-Scripts.git
cd Assignment4-Stats-Scripts
Create the Conda Environment

bash
conda env create -f environment.yml
conda activate stats-env

Or, if using pip:
bash
pip install -r requirements.txt
Launch Jupyter Lab

bash
jupyter lab
Then open the notebook located at notebooks/stats_python.ipynb.
```

## Usage
Each code example from the tutorial is placed in its own notebook cell.

Markdown cells are used for headers, explanations, and context.

All code blocks include detailed inline comments.

Example datasets are downloaded automatically or loaded from local text files.

Visualizations demonstrate relationships between variables, statistical effects (e.g., gender, year), and modeling outputs using ols.

## Project Structure
This project consists of one main Jupyter notebook and supporting setup files to recreate the environment. The notebook is organized into thematic sections matching the tutorial (e.g., correlation, regression, visualization).

## License
This repository is intended for educational use only as part of the BSGP-7030 Data Science course.

## Acknowledgments
This work is based on the open-access tutorial:
Statistics in Python – Gaël Varoquaux
Available at: https://scipy-lectures.org/packages/statistics/index.html
© The SciPy Lecture Notes authors

Please cite the original authors if you reuse or build upon this material.
