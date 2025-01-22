Churn Analysis for Subscription Services

This repository showcases an end-to-end analysis of customer churn for a subscription-based service. The project uses Python to clean, visualize, and model data, providing actionable insights into churn behavior.

Key Highlights

Data Cleaning:

Fixed missing values in both numerical and categorical features.

Converted inconsistent data into a usable format for analysis.

Exploratory Data Analysis (EDA):

Delivered insightful visualizations, including distribution plots, box plots, and heatmaps.

Explored relationships between customer behavior and churn.

Feature Engineering:

Encoded categorical variables for seamless model integration.

Standardized numerical features for better machine learning performance.

Machine Learning:

Built a baseline churn prediction model using Logistic Regression.

Assessed performance with classification metrics and ROC-AUC curves.

Visualizations:

Confusion Matrix

ROC Curve

Monthly Charges Distribution

Subscription Type vs. Churn

Viewing Hours by Churn

Feature Correlation Heatmap

Payment Method vs. Churn Rate

Multi-Device Access vs. Churn

Getting Started

Prerequisites

Ensure you have the following:

Python 3.7 or later

Libraries: pandas, numpy, matplotlib, seaborn, sklearn

Installation Steps

Clone this repository:

git clone https://github.com/Deepaananthan2004/-Data-Analytics-Internship-in-codec.git

Navigate to the project folder:

cd -Data-Analytics-Internship-in-codec

Install the required dependencies:

pip install -r requirements.txt

Usage

Add your datasets (train.csv and test.csv) to the root directory.

Run the main analysis script:

python churn_analysis.py

Outputs:

Visualizations are saved in the plots/ folder.

Cleaned datasets are stored as processed_train.csv and processed_test.csv.

Project Structure

-Data-Analytics-Internship-in-codec/
├── data/
│   ├── train.csv         # Training dataset
│   ├── test.csv          # Testing dataset
├── plots/                # Folder for generated visualizations
├── churn_analysis.py     # Main script for analysis
├── requirements.txt      # List of required Python libraries
└── README.md             # Project documentation

Key Findings

From this analysis, we discovered:

Customers with shorter subscription durations are more likely to churn.

Higher monthly charges are associated with increased churn rates.

Features like subscription type, payment method, and multi-device access significantly influence churn behavior.

Contributing

We welcome contributions! To contribute:

Fork this repository.

Create a feature branch.

Submit a pull request.

Your feedback and suggestions are invaluable.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Special thanks to:

The subscription service for providing the data.

Python's robust libraries for making data analysis and visualization easier.
