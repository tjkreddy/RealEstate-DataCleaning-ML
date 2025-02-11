# RealEstate-DataCleaning-ML

## Project Overview
This project focuses on preprocessing a Gurgaon real estate dataset to enhance data quality for analysis and machine learning models. The primary objectives include handling missing values, detecting and managing outliers, and ensuring data integrity. The cleaned dataset improves predictive accuracy for real estate analytics.

## Features
- **Data Cleaning:** Handles missing values using KNN imputation and mode filling for categorical columns.
- **Outlier Detection & Handling:** Uses Z-score analysis and Winsorization to manage extreme values.
- **Statistical Analysis:** Computes skewness, kurtosis, and variance to understand data distribution.
- **Data Visualization:** Generates histograms, box plots, and scatter plots for insights.
- **Multivariate Analysis:** Examines relationships between key features and price.

## Dataset
The dataset consists of real estate property details, including:
- **Numerical Features:** Price, area, luxury score, floor number, etc.
- **Categorical Features:** Property type, society, furnishing type, etc.
- **Derived Features:** Price per sqft, age of possession, etc.

## Notebooks
- **Brownie_G_272_273_277_298.ipynb:** Contains data exploration, visualization, and preprocessing steps.
- **G_272_273_277_298_code.ipynb:** Implements data cleaning, outlier handling, and final dataset preparation.

## Technologies Used
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Techniques:** KNN Imputer, Z-score, Winsorization

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RealEstate-DataCleaning-ML.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter notebooks in your preferred environment.

## Teammates
1. Parthiv Reddy -- SE22UCSE298 
2. Lakshmi Reddy -- SE22UCSE277
3. Jugal Kishore Reddy -- SE22UCSE272
4. Thannoj -- SE22UCSE273

## Results 
- Missing values successfully handled, reducing data inconsistencies.
- Outliers managed effectively, improving dataset reliability.
- Enhanced data quality for better ML model performance.

## Contributing
Contributions are welcome! Feel free to fork the repo and submit pull requests.

## License
This project is licensed under the MIT License .

