# Job Transition Analytics Project

This repository contains a synthetic dataset and a Jupyter notebook that demonstrate key skills for business analyst, program manager and data analyst roles. The project is designed to be used out-of-the-box: clone the repository, install the dependencies and start exploring.

## Dataset

The `synthetic_dataset.csv` file provides a fabricated record of orders for a fictional company. Each row represents a single order. The columns include:

| Column | Description |
|------|-------------|
| **OrderDate** | Date the order was placed (YYYY-MM-DD) |
| **Region** | Geographic region where the order was sold (`North`, `South`, `East`, `West`) |
| **Product** | Product name (`Product_A`, `Product_B`, `Product_C`, `Product_D`) |
| **Category** | Product category (`Electronics`, `Furniture`, `Office Supplies`) |
| **UnitsSold** | Number of units sold |
| **UnitPrice** | Price per unit (USD) |
| **Revenue** | Total revenue (`UnitsSold x UnitPrice`) |
| **Cost** | Manufacturing or purchase cost |
| **Profit** | Revenue minus cost |
| **OnTimeDelivery** | 1 if the order was delivered on time, otherwise 0 |

The dataset contains **100 rows** and can be easily extended or adjusted to test different analyses.

## Notebook

The Jupyter notebook `analysis.ipynb` walks through an end-to-end analysis. It includes:

1. **Data Loading & Inspection** – reading the CSV, parsing dates and viewing summary statistics.
2. **Exploratory Data Analysis (EDA)** – visualisations such as revenue by region, revenue trends over time and a correlation heatmap of numeric variables.
3. **Predictive Modeling** – training a simple linear regression model to predict revenue from units sold and unit price, and evaluating the model’s performance.
4. **Conclusions** – discussion of insights gleaned from the EDA and model.

The notebook serves as a template for presenting analytical findings to stakeholders. Feel free to expand it by exploring other relationships (e.g., profit forecasting, delivery performance) or trying more complex models.

## Getting Started

To run the notebook on your own machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shreyapatil9480/job-transition-analytics-project.git
   cd job-transition-analytics-project
   ```
2. **Install dependencies** (ideally in a virtual environment) using the provided requirements file:
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook analysis.ipynb
   ```
   Or use JupyterLab if you prefer:
   ```bash
   jupyter lab
   ```
4. **Explore & Extend** – run the notebook cells to reproduce the EDA and model results. Then try modifying the analysis to answer new questions or add more charts and models.

## License

This project uses a synthetic dataset created solely for demonstration purposes and is provided under the MIT License. You may use, modify and distribute the code and dataset without restriction.
