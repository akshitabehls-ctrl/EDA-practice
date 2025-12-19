📖 Overview

Exploratory Data Analysis (EDA) on two datasets: Titanic and Tips, using Python.
This project focuses on understanding data distributions, patterns, correlations, and visual insights using common EDA workflows.

📂 Files
├── eda-practice.ipynb
├── README.md
└── requirements.txt

📊 Datasets

1️⃣ Titanic Dataset

Survival dataset (Age, Fare, Sex, Pclass, etc.)

Focus: distributions, missing values, survival patterns

2️⃣ Tips Dataset

Restaurant tipping dataset

Focus: correlations, categorical patterns, spending behavior

Datasets sourced via Seaborn.

🧰 Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📈 Analysis Highlights

Summary statistics

Missing value inspection

Distribution analysis

Correlation heatmaps

Outlier checks

Visual comparisons

📍 Key Insights

Titanic:

Survival varies clearly by gender + class

Age + fare show skewness

Missing values concentrated in Age/Cabin

Tips:

Strong link between total bill + tip

Tipping behavior varies by sex/smoking/time

Weekend bills are higher

🔧 How to Run
pip install -r requirements.txt
jupyter notebook eda-practice.ipynb
