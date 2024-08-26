# Ecommerce User Behaviour Analysis

![GitHub license](https://img.shields.io/github/license/karanzaveri/Ecommerce-User-Behaviour)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Project Overview

This project aims to analyze user behavior on an ecommerce platform. By examining user interactions, such as product views, clicks, and purchases, the goal is to identify patterns that can help in optimizing user experience, improving conversion rates, and making data-driven decisions for business growth.

## Features

- **Data Collection**: The project uses a dataset that captures user interactions on an ecommerce platform.
- **Data Preprocessing**: Includes handling missing values, normalizing data, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: In-depth analysis of the dataset to uncover trends and patterns.
- **Feature Engineering**: Creation of new features to improve the predictive power of the models.
- **Machine Learning Models**: Building and evaluating models to predict user actions like purchases.
- **Data Visualization**: Provides insightful visualizations to present the findings.

## Installation

To set up this project on your local machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/karanzaveri/Ecommerce-User-Behaviour.git
    cd Ecommerce-User-Behaviour
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After installation, you can explore the project by running the following notebooks and scripts:

1. **Data Exploration**:
   - Open the Jupyter notebook `EDA.ipynb` to explore the dataset and identify key trends and patterns.

2. **Running Models**:
   - Use `model_training.ipynb` to train machine learning models on the dataset.

3. **Report Generation**:
   - Generate detailed reports of your analysis using `report_generation.ipynb`.

4. **Visualizations**:
   - Review visualizations in the `visualizations/` directory to better understand the results.

## Project Structure

Here is an overview of the project structure:

    Ecommerce-User-Behaviour/ ├── data/ │ ├── raw_data.csv # Raw dataset │ └── processed_data.csv # Cleaned and processed dataset ├── notebooks/ │ ├── EDA.ipynb # Exploratory Data Analysis │ ├── model_training.ipynb # Machine Learning Model Training │ └── report_generation.ipynb # Report Generation ├── visualizations/ │ ├── plots/ # Directory containing generated plots ├── src/ │ ├── data_processing.py # Data cleaning and processing scripts │ ├── feature_engineering.py # Feature engineering scripts │ └── model.py # Machine learning models ├── requirements.txt # Python dependencies └── README.md # Project README file


## Technologies Used

- **Python**: The primary programming language for the project.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Jupyter Notebook**: For interactive analysis and documentation.

## Dataset Description

### Overview

The dataset used in this project contains records of user interactions on an ecommerce platform. Each record represents a single interaction, such as a product view, a click, or a purchase.

### Key Attributes

- **User ID**: Unique identifier for each user.
- **Session ID**: Identifier for a user session.
- **Timestamp**: The time of the interaction.
- **Product ID**: Identifier for the product involved in the interaction.
- **Action**: Type of interaction (e.g., view, click, purchase).

### Data Sources

If applicable, provide links or references to where the data was obtained. Mention any preprocessing steps taken to clean and prepare the data for analysis.

## Data Preprocessing

Before performing any analysis, the data was preprocessed as follows:

- **Handling Missing Values**: Missing data were imputed or removed based on the context.
- **Normalization**: Numeric features were scaled to improve model performance.
- **Categorical Encoding**: Categorical variables were encoded using one-hot encoding or label encoding.

## Exploratory Data Analysis (EDA)

EDA is a critical step in understanding the underlying patterns and trends in the dataset. In this project, the EDA includes:

- **Distribution Analysis**: Studying the distribution of key variables.
- **Correlation Analysis**: Identifying relationships between different features.
- **Time Series Analysis**: Examining trends over time, such as seasonal effects or spikes in user activity.
- **User Segmentation**: Grouping users based on behavior to identify distinct user profiles.

## Feature Engineering

To enhance the predictive power of the models, several new features were created, including:

- **Interaction Count**: The total number of interactions a user had.
- **Time Spent**: The total time spent by a user on the platform.
- **Product Category**: Derived from product IDs to capture category-level interactions.

## Modeling

The project involves building and evaluating several machine learning models, including:

- **Logistic Regression**: For binary classification tasks.
- **Random Forest**: For capturing complex relationships between features.
- **Gradient Boosting**: For improving model performance on imbalanced datasets.

Each model was trained and evaluated using cross-validation, and the results were compared to select the best-performing model.

## Evaluation Metrics

The models were evaluated using several metrics, including:

- **Accuracy**: The proportion of correct predictions.
- **Precision and Recall**: To balance false positives and false negatives.
- **F1 Score**: The harmonic mean of precision and recall.
- **ROC-AUC**: The area under the ROC curve to assess model discrimination.

## Results

The key findings from the analysis include:

- **User Behavior Patterns**: Identified common paths users take before making a purchase.
- **Predictive Modeling**: Successfully predicted user purchases with a certain accuracy.
- **Feature Importance**: Highlighted the most critical features influencing user decisions.

## Visualization

Visualizations are provided to illustrate the key insights and findings from the analysis. These include:

- **User Interaction Heatmaps**: To show the intensity of interactions across different time periods.
- **Feature Importance Plots**: To visualize which features have the most impact on predictions.
- **ROC Curves**: To compare the performance of different models.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact Information

If you have any questions, suggestions, or feedback, feel free to reach out:

- **Name**: Karan Zaveri
- **Email**: [your-karanzaveri92@gmail.com](mailto:karanzaveri92@gmail.com)
- **LinkedIn**: [Karan Zaveri](https://www.linkedin.com/in/karanzaveri92)
