# FinTech 545 Final Project

This project contains the full solution to the FinTech 545 Final Project assignment, including a complete PDF report with detailed explanations and a fully executable Jupyter Notebook implementing all parts of the project.

##  Contents

- **Final Project.pdf** – The written report with comprehensive results, formulas, and discussions.
- **FinalProject.ipynb** – The Jupyter Notebook with Python code for all calculations and simulations.
- **initial_portfolio.csv**, **DailyPrices.csv**, **rf.csv** – Required datasets.
- **README.md** – This instruction file.

##  Project Overview

The project involves modeling portfolio performance and risk using CAPM, fitting asset return distributions, and constructing optimized portfolios under various constraints. It is divided into five main parts:

1. **Part 1** – CAPM regression and return/risk attribution for given portfolios.
2. **Part 2** – Construction of optimal Sharpe ratio portfolios using CAPM betas.
3. **Part 3** – Investigation of NIG and Skew Normal distributions in financial modeling.
4. **Part 4** – Risk modeling and simulation using Copulas and fitted distributions.
5. **Part 5** – Construction of ES-based Risk Parity portfolios and full return/risk attribution using simulated tail-risk and CAPM betas.

## How to Run

To run the code:

1. Make sure you have **Python (>=3.8)** installed along with **Jupyter Notebook**.
2. Download the required dataset files (`initial_portfolio.csv`, `DailyPrices.csv`, `rf.csv`) from the course repository or your instructor and place them in the same directory as the notebook.
3. Open the notebook `FinalProject.ipynb` in Jupyter and run the cells step by step.
4. Alternatively, you can export the notebook as a `.py` script and execute it from the command line.

##  Notes

- The final portfolio optimization in Part 5 uses Expected Shortfall (ES) as the risk measure and Gaussian Copula for simulation.
- Attribution results (return and risk) are compared across Part 1 (original portfolios), Part 2 (maximum Sharpe portfolios), and Part 5 (risk parity portfolios).
- All results, formulas, and financial interpretations are documented in the PDF report.




