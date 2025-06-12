# Netflix Titles Analysis and Classification

## Project Overview
This project analyzes Netflix's movie and TV show content dataset to uncover insights about their catalog and builds classification models to predict content type (Movie vs TV Show).

## Dataset
The dataset contains information about Netflix movies and TV shows including:
- Title, director, cast
- Country of production
- Date added to Netflix
- Release year
- Rating
- Duration
- Categories

## Analysis Steps

### 1. Data Preprocessing
- Handled missing values by imputing with mode for categorical features
- Converted date fields to datetime format
- Extracted numerical values from duration strings
- Created additional features (year_added, month_added)

### 2. Exploratory Data Analysis (EDA)
- Visualized distribution of Movies vs TV Shows
- Identified top content-producing countries
- Analyzed most common categories
- Examined content addition trends over time
- Compared durations of Movies vs TV Shows
- Explored relationship between release year and addition year
- Analyzed content ratings distribution
- Identified top directors
- Examined exclusive content by country
- Investigated seasonality in content additions

### 3. Machine Learning Modeling
- Encoded categorical variables using Label Encoding
- Scaled features using StandardScaler
- Split data into training and test sets (80/20)
- Evaluated 10 different classification algorithms:
  - SVM
  - Random Forest
  - Gradient Boosting
  - AdaBoost
  - KNN
  - Logistic Regression
  - Decision Tree
  - Naive Bayes
  - LDA
  - MLP Neural Network

## Key Results
The best performing models achieved accuracy of XX% in classifying content as Movies or TV Shows. Detailed performance metrics are available in the results CSV file.

## Technologies Used
- Python 3
- Pandas (Data manipulation)
- Matplotlib/Seaborn (Visualization)
- Scikit-learn (Machine Learning)

## How to Run
1. Install required packages: `pip install pandas matplotlib seaborn scikit-learn`
2. Download the dataset from Kaggle
3. Run the analysis script: `python netflix_analysis.py`
