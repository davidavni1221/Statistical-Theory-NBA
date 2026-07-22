# NBA Team Success Analysis: Efficiency, Volume, and the 3-Point Revolution 🏀

This repository contains the complete dataset and Python code for our Statistical Theory final project. The analysis investigates the statistical drivers of NBA team success, contrasting shooting efficiency with scoring volume, and rigorously testing the structural impact of the modern "3-Point Revolution".

## Repository Structure
* `regular_season_totals_2010_2024.csv`: The aggregated team-season dataset (420 rows) used for the analysis.
* `NBA_Analysis_Project.ipynb`: The main Jupyter Notebook containing all data processing, visualizations, and advanced statistical tests.
* `README.md`: Project documentation and reproduction instructions.

## Statistical Methods Implemented
This project applies several advanced statistical tools from the course syllabus:
* **Bivariate Analysis:** Pearson correlations, 95% Confidence Intervals.
* **Multiple Comparisons:** Bonferroni correction for Type I error control.
* **Parametric Tests:** D'Agostino's K-squared normality test, Independent Samples Welch’s T-test (One-Sided), Effect Size (Cohen's d), and Statistical Power analysis.
* **Multivariate Modeling:** Ordinary Least Squares (OLS) Multiple Linear Regression with interaction terms and F-tests.
* **Classification:** Logistic Regression evaluated via Confusion Matrix, Accuracy, Precision, and Recall.
* **Advanced Inference:** Generalized Likelihood Ratio Test (GLRT) and Wald Sequential Probability Ratio Test (SPRT) with stopping time analysis.

## Prerequisites
To run the analysis locally, ensure you have Python 3 installed along with the following libraries:
* `pandas`
* `numpy`
* `scipy`
* `statsmodels`
* `scikit-learn`
* `matplotlib`
* `seaborn`

You can install the required packages using:
```bash
pip install pandas numpy scipy statsmodels scikit-learn matplotlib seaborn

## How to Reproduce the Analysis

### Option 1: Running in Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File > Upload notebook** and upload the `NBA_Analysis_Project.ipynb` file from this repository.
3. The notebook is configured to automatically fetch the dataset via URL.
4. Click **Runtime > Run all** to execute the analysis and generate all statistical tables and plots.

### Option 2: Running Locally
1. Clone this repository to your local machine:
   git clone https://github.com/davidavni1221/Statistical-Theory-NBA.git

2. Navigate to the project directory.
3. Open `NBA_Analysis_Project.ipynb` in your preferred IDE (e.g., PyCharm, VS Code, or Jupyter Notebook).
4. Run the cells sequentially to reproduce the results.
