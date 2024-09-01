# Data-Driven Supply Chain Solution

## Project Overview

This project aims to analyze and optimize supply chain operations for 100 SKUs. By leveraging data preprocessing, exploratory data analysis (EDA), and machine learning techniques, this project identifies inefficiencies, recommends improvements, and enhances overall supply chain performance.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Analysis and Modeling](#data-analysis-and-modeling)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The project involves analyzing supply chain data for 100 SKUs to uncover inefficiencies and optimize various aspects of the supply chain. Key tasks include data preprocessing, exploratory data analysis (EDA), risk assessment, and optimization of economic order quantities (EOQ). Machine learning techniques are employed for forecasting stock levels, transportation costs, and demand, alongside evaluating key performance indicators (KPIs).

## Features

- **Data Preprocessing & EDA:** Utilized correlation and pairwise plots to analyze feature distributions and relationships.
- **Product, Route, and Quality Control Analyses:** Conducted detailed analyses to enhance supply chain efficiency.
- **Supply Chain Risk Assessment:** Identified potential risks and developed mitigation strategies.
- **Optimization:** Calculated EOQ for SKUs and optimized various supply chain parameters.
- **Machine Learning Models:** Applied LightGBM for sales forecasting and KNN for route optimization.
- **Performance Evaluation:** Achieved an RMSE of 37% in sales forecasting.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for EDA and visualization)
- Scikit-learn
- LightGBM
- KNN (K-Nearest Neighbors)

## Data Analysis and Modeling

### Data Preprocessing & EDA

- **Data Preprocessing:** Cleaned and transformed data for analysis.
- **Exploratory Data Analysis (EDA):** Used correlation matrices and pairwise plots to explore feature relationships.

### Machine Learning Models

- **Sales Forecasting:** Implemented LightGBM to predict sales, achieving an RMSE of 37%.
- **Route Optimization:** Used a KNN model to suggest optimal transportation routes.

## Results

- **Sales Forecasting RMSE:** Achieved an RMSE of 37% using LightGBM.
- **Route Optimization:** Identified optimal routes for transportation using KNN.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
