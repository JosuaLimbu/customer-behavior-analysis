# Data Analysis

## Customer Behavior Analysis

This repository contains code for analyzing customer behavior data using the Customer Personality Analysis dataset. The dataset can be found [here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).

### Getting Started

This repository uses Python 3.11

- The `requirements.txt` is provided to install dependencies easily.

### Usage

1. Download and install **Anaconda** from [here](https://www.anaconda.com/docs/getting-started/anaconda/install).
2. Open Anaconda and create a new environment:

```bash
conda create --name customer_analysis python=3.11
conda activate customer_analysis
```

3. Install Jupyter Notebook:

```bash
conda install -c conda-forge jupyterlab
```

4. Install all dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

5. Download the dataset from [here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) and place it in the same directory as the analysis code.
6. Run the Jupyter Notebook to analyze customer behavior:

```bash
jupyter notebook customer-behavior-analysis.ipynb
```

7. Follow the instructions in the notebook to preprocess data, analyze customer segments, and derive insights.
