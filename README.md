# Algorithmic Trading Quantitative Analysis

## Project Overview

This project focuses on analyzing the stock performance of various companies within the AI industry. The goal is to identify investment opportunities by examining long-term growth potential and technological advancements in companies that are making significant impacts across different sectors of the AI industry.

## Files in the Repository

-   **Algorithmic_Analysis_AI_Tech.ipynb**: A Jupyter notebook containing the code and markdown cells where the analysis is performed and documented.

## Technologies Used

-   **Python**: The main programming language used for analysis.
-   **pandas**: A library for data manipulation and analysis.
-   **NumPy**: A library for large, multi-dimensional arrays and matrix operations.
-   **Matplotlib**: A plotting library for creating static, interactive, and animated visualizations in Python.
-   **yfinance**: A library to fetch historical market data from Yahoo Finance.

## Setup and Installation

To run this project within a virtual environment, follow these steps:

1. **Clone the Repository**:
   Clone this repository to your local machine or download the files directly.

2. **Create and Activate a Virtual Environment**:

    - Navigate to the project directory.
    - Create a virtual environment:
        ```bash
        python -m venv venv
        ```
    - Activate the virtual environment:
        - Windows: `.\venv\Scripts\activate`
        - macOS/Linux: `source venv/bin/activate`

3. **Install Dependencies**:
   Install all dependencies using the `requirements.txt` file:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Notebook

To start the Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the directory containing the notebook file `Algorithmic_Analysis_AI_Tech.ipynb` and open it.

## Notebook Structure

-   **Stage 1: Background**: Discussion on the motivations for investing in AI companies and the strategy for selecting a diversified basket of stocks.
-   **Stage 2: Fetch Stock Data for Multiple Companies**: Code to download historical stock data for selected AI companies.
-   **Stage 3: Data Manipulation**: Analysis of the downloaded data, focusing on closing prices and other relevant financial metrics.

## Data Analysis

The data analysis is performed on stock data fetched for multiple AI companies, including NVIDIA, Tesla, and others. The analysis includes:

-   Fetching historical stock data using yfinance.
-   Extracting and visualizing closing prices.
-   Additional analysis might include calculating returns, volatility, and other financial metrics.
