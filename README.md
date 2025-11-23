# Data Governance Project - Titanic Dataset Analysis

Ce projet a été réalisé dans le cadre d'une formation de Master en gouvernance de données. Il présente un travail pratique d'analyse et de gouvernance de données axé sur le dataset Titanic, démontrant les techniques de préparation, de nettoyage, de prétraitement et d'analyse exploratoire des données.

*This project was completed as part of a Master's program in Data Governance. It presents practical work on data analysis and governance focused on the Titanic dataset, demonstrating data preparation, cleaning, preprocessing, and exploratory data analysis techniques.*

## 🎓 Academic Context

Ce travail a été réalisé dans le cadre d'une formation de Master en gouvernance de données, encadré par le professeur [Mohamed el far](https://scholar.google.com/citations?user=nS0-eWYAAAAJ&hl). Il représente un exercice académique pratique visant à appliquer les principes et les meilleures pratiques de la gouvernance de données dans un contexte réel.

*This work was completed as part of a Master's program in Data Governance, supervised by Professor [Mohamed el far](https://scholar.google.com/citations?user=nS0-eWYAAAAJ&hl). It represents a practical academic exercise aimed at applying data governance principles and best practices in a real-world context.*

## 📋 Table of Contents

- [Academic Context](#academic-context)
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Contributing](#contributing)

## 🎯 Overview

Ce projet fait partie d'un atelier de gouvernance de données (Atelier 1) réalisé dans le cadre d'un Master universitaire. Il explore divers aspects de la qualité des données, du nettoyage et du prétraitement des données en utilisant le célèbre dataset Titanic. 

*This project is part of a data governance workshop (Atelier 1) completed as part of a university Master's program. It explores various aspects of data quality, data cleaning, and data preprocessing using the famous Titanic dataset.*

Le projet inclut des implémentations pratiques de :

- Data loading and exploration
- Missing value analysis and imputation
- Duplicate detection and handling
- Data normalization and transformation
- Categorical variable encoding
- Anomaly detection through visualization
- Data quality assessment

## ✨ Features

- **Comprehensive Data Exploration**: Initial analysis of the Titanic dataset structure and statistics
- **Missing Data Handling**: Multiple imputation techniques including:
  - Simple Imputer
  - KNN Imputer
  - Iterative Imputer
- **Data Preprocessing**: 
  - Standardization and normalization (StandardScaler, MinMaxScaler)
  - Label encoding and one-hot encoding for categorical variables
- **Data Visualization**: Visual analysis for anomaly detection using matplotlib and seaborn
- **Duplicate Detection**: Identification and handling of duplicate records
- **Data Quality Metrics**: Assessment of data completeness and accuracy

## 📁 Project Structure

```
gouvernance_de_donnees/
│
├── Atelier 1.pdf           # Workshop instructions and guidelines
├── Titanic_dataset.csv     # The Titanic dataset
├── tp1.ipynb               # Main analysis notebook (French version)
├── zaim_med.ipynb          # Alternative analysis notebook
├── requirements.txt        # Python dependencies
└── README.md               # This file
```

## 🛠️ Technologies Used

- **Python 3.x**: Main programming language
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **seaborn**: Statistical data visualization
- **matplotlib**: Plotting and visualization
- **scikit-learn**: Machine learning utilities including:
  - Data imputation techniques
  - Data preprocessing and scaling
  - Encoding methods

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/MedZaim/gouvernance_de_donnees.git
cd gouvernance_de_donnees
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open either notebook:
   - `tp1.ipynb` - Comprehensive French version with detailed analysis
   - `zaim_med.ipynb` - Alternative analysis approach

3. Run the cells sequentially to:
   - Load and explore the Titanic dataset
   - Apply data cleaning techniques
   - Visualize data quality issues
   - Transform and prepare data for analysis

## 📊 Dataset

The project uses the **Titanic dataset** (`Titanic_dataset.csv`), which contains information about passengers aboard the Titanic. The dataset includes:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 📓 Notebooks

### tp1.ipynb
Main analysis notebook covering:
1. Library importation
2. Data loading
3. Initial data exploration
4. Missing value management
5. Duplicate detection and handling
6. Data normalization and transformation
7. Categorical variable processing
8. Visualization for anomaly detection

### zaim_med.ipynb
Alternative approach focusing on:
1. Importing libraries
2. Loading the dataset
3. Exploratory data analysis
4. Different types of missing values and their treatment

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

## 👨‍💻 Author

**Med Zaim**
- GitHub: [@MedZaim](https://github.com/MedZaim)

## 📝 License

This project is available for educational purposes as part of a Master's program data governance course.

---

**Note**: Ce projet est conçu à des fins éducatives pour démontrer les principes de gouvernance de données et les meilleures pratiques en analyse de données. / *This project is designed for educational purposes to demonstrate data governance principles and best practices in data analysis.*
