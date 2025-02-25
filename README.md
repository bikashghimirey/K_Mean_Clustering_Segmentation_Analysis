#K-Means Segmentation Analysis

📌 **Project Overview**
This project applies K-Means Clustering to segment countries based on Life Expectancy, GDP per Capita, and Population. The analysis helps identify patterns in global economic development and health outcomes, providing insights for policymakers and researchers.

📊 **Objective**

  -Cluster countries into meaningful segments based on their economic and demographic factors.

  -Use unsupervised learning to explore similarities among nations.

  -Provide data-driven insights into global disparities and economic structures.

🗂 **Dataset**
  Source: [UN Life Expectancy & GDP Dataset (2023)](https://raw.githubusercontent.com/siglimumuni/Datasets/refs/heads/master/UN_Life_Exp_vs_GDP_per_Capita_2023%20-%20UN_Life_Exp_vs_GDP_per_Capita_2023_2%20-%20UN_Life_Exp_vs_GDP_per_Capita_2023%20-%20UN_Life_Exp_vs_GDP_per_Capita_2023_2.csv)

  Features Used: Life Expectancy (Years), GDP per Capita, Population

🛠 **Technologies & Libraries Used**

  Python 🐍

  Pandas & NumPy 📊

  Matplotlib & Seaborn 🎨

  Scikit-Learn 🤖

🔍 **Exploratory Data Analysis (EDA)**

  Data Cleaning: Checked for missing values and ensured data integrity.

  Visualization: Histograms, scatter plots, and heatmaps to understand data distribution.

  Log Transformation: Applied to GDP per Capita and Population to reduce skewness.

🔢 **Clustering Approach**

  Normalization: StandardScaler was applied to standardize numerical features.

  Elbow Method: Used to determine the optimal number of clusters.

  K-Means Clustering: Implemented with k=6 based on the elbow curve.

  Segmentation Labels: Assigned meaningful names to clusters based on economic and demographic traits.

📊 **Segmentation Results**

  Segment	Characteristics

  Segment Alpha A	High-income, developed nations with high life expectancy.

  Segment Alpha B	Emerging economies with improving health outcomes.

  Segment Beta	Low-income countries with economic and healthcare struggles.

  Segment Gamma	Rapidly growing economies with large populations.

  Segment Delta	Small but stable economies with a high standard of living.

  Segment Epsilon	Outlier is facing extreme socio-economic challenges.

📈 **Visualizations**

  Elbow Method Curve to determine the best number of clusters.

  3D Scatter Plot for visualizing cluster separation.

  Heatmaps & Pairplots to analyze relationships between variables.

🚀 **How to Run the Project**

  1. Clone the repository:
    git clone https://github.com/yourusername/K_Mean_Clustering_Segmentation_Analysis.git
    cd K_Mean_Clustering_Segmentation_Analysis

  2. Install dependencies:
     pip install numpy pandas matplotlib seaborn scikit-learn
     
  4. Run the Python Script:
     python segmentation_analysis.py

📌 **Future Enhancements**

  Experiment with Hierarchical Clustering for alternative segmentation.

  Use Principal Component Analysis (PCA) to reduce dimensionality.

  Incorporate additional socio-economic indicators (e.g., literacy rate, healthcare access).

🏆 **Contributors**

  **Bikash Ghimirey**
