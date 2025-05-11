# E-Commerce Client Segmentation

## Overview
This project implements customer segmentation analysis on an e-commerce dataset to identify distinct customer groups and their purchasing behaviors. By leveraging unsupervised machine learning techniques, particularly clustering algorithms, we identify natural groupings of customers with similar characteristics, enabling targeted marketing strategies and personalized customer experiences.

## Features
- **Data Exploration & Preprocessing**: Comprehensive data cleaning, handling missing values, and feature engineering
- **Unsupervised Learning**: Implementation of clustering algorithms (K-means, Hierarchical)
- **Feature Importance Analysis**: Determination of which features best differentiate customer segments
- **Interactive Visualizations**: Visual representations of customer segments and their characteristics
- **Business Insights**: Actionable recommendations based on segmentation results

## Tech Stack
- **Python 3.8+**
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Interactive Components**: IPython widgets

## Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/carlosgutierrezch/client-segmentation.git
   cd client-segmentation
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Data Preparation
The project uses a customer transaction dataset stored in `data.csv`. The dataset contains transaction records with customer IDs, purchase amounts, timestamps, and other behavioral metrics.

### Running the Analysis
1. Open the Jupyter notebook:
   ```bash
   jupyter notebook test/exploration_modeling.ipynb
   ```

2. Execute the cells sequentially to:
   - Load and preprocess the data
   - Explore customer patterns
   - Perform clustering analysis
   - Visualize customer segments
   - Generate insights

## Project Structure
```
client-segmentation/
├── data.csv                  # E-commerce customer dataset
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── test/
    └── exploration_modeling.ipynb  # Main analysis notebook
```

## Data Dictionary

The dataset contains the following key fields:
- **Customer ID**: Unique identifier for each customer
- **Purchase Amount**: Monetary value of transactions
- **Purchase Frequency**: Number of transactions per time period
- **Recency**: Time since last purchase
- **Product Categories**: Types of products purchased
- **Customer Location**: Geographic information

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Feature scaling and normalization
   - Outlier detection and treatment

2. **Exploratory Data Analysis**:
   - Distribution analysis
   - Correlation studies
   - Pattern identification

3. **Customer Segmentation**:
   - Algorithm selection and parameter tuning
   - Optimal cluster determination
   - Segment profiling and interpretation

4. **Business Applications**:
   - Targeted marketing campaigns
   - Personalized recommendations
   - Customer retention strategies

## Future Improvements
- Implementation of more sophisticated clustering algorithms
- Integration of additional customer data sources
- Development of a real-time segmentation dashboard
- Predictive modeling for customer lifetime value by segment

## License
This project is licensed under the terms of the included LICENSE file.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
