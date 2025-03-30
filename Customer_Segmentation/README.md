# Customer Segmentation Analysis

This project contains a customer segmentation analysis based on marketing campaign data. The project utilizes advanced machine learning techniques to identify and analyze different customer segments.

## Project Structure

- `customer_segmentation.ipynb` - main analysis notebook
- `marketing_campaign.csv` - dataset
- `requirements.txt` - project dependencies

## Requirements

The project requires the following Python libraries:
- pandas >= 1.5.0
- numpy >= 1.21.0
- matplotlib >= 3.5.0
- seaborn >= 0.11.0
- scikit-learn >= 1.0.0
- scipy >= 1.7.0

## Installation

1. Clone the repository:
```bash
git clone [REPOSITORY_URL]
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the `customer_segmentation.ipynb` notebook in Jupyter Notebook or JupyterLab
2. Run all cells in sequence to perform the complete customer segmentation analysis

## Analysis Steps

The analysis in the notebook follows these key steps:

### 1. Data Loading and Exploration
- Importing necessary libraries
- Loading the dataset
- Examining data structure and statistical summaries
- Identifying and handling missing values

### 2. Data Preprocessing
- Feature selection for segmentation
- Data cleaning and transformation
- Standardization of features
- Handling outliers

### 3. Segmentation with K-Means Clustering
- Determining optimal number of clusters using the Elbow Method
- Building the K-Means model
- Assigning customer segments
- Dimensionality reduction with PCA for visualization

### 4. Segment Analysis and Profiling
- Calculating segment statistics
- Creating visualizations to compare segments
- Identifying key differences between segments
- Interpreting behavior patterns

### 5. Marketing Recommendations
- Developing targeted strategies for each segment
- Creating actionable insights
- Suggesting campaign optimization approaches
- Measuring potential business impact

## Data Structure

The `marketing_campaign.csv` dataset contains customer information, including:
- Demographic data
- Purchase behavior
- Marketing campaign interactions

## Results

The project provides a detailed analysis of customer segments, including:
- Main segment identification
- Segment characteristics
- Visualizations and descriptive statistics
- Marketing recommendations for each segment 