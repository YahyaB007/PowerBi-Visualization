# PowerBi-Visualization

## 1. Project Title

🌸 Iris Flower Classification & Clustering Dashboard
An interactive Power BI dashboard built on the Iris dataset to analyze species characteristics, clustering patterns, and dimensionality reduction insights.

## 2. Short Description

The Iris Dashboard provides a detailed analytical view of the Iris dataset by visualizing species-specific averages, cluster distributions, and principal component analysis (PCA). It helps data scientists, students, and analysts explore the relationships between petal/sepal dimensions and species classification.

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main visualization and reporting tool.

• 📂 iris.csv – Dataset containing measurements of 3 Iris flower species.

• 🧠 DAX (Data Analysis Expressions) – Used to calculate averages, sums, and cluster metrics.

• 📈 PCA (Principal Component Analysis) – Dimensionality reduction applied to visualize species separation.

• 📁 File Format – .pbix for the Power BI project and .png for dashboard preview/export.


## 4. Data Source

Source: **Iris Dataset (iris.csv)**

This classic dataset contains 150 observations across 3 species of Iris flowers (Setosa, Versicolor, Virginica) with the following attributes:

🌸 Sepal Length

🌸 Sepal Width

🌸 Petal Length

🌸 Petal Width

🌸 Species Label

Additionally, clustering analysis and PCA transformation were applied to uncover hidden patterns and visualize separability.

## 5. Features 

#### • Business Problem

Understanding species classification in biology often requires analyzing multiple features simultaneously. Manual analysis of sepal and petal dimensions makes it difficult to identify unique patterns or visualize separability across species.


#### • Goal of the Dashboard

To deliver a visual learning and analytical tool that:


Summarizes species-wise petal/sepal averages.


Shows cluster distribution across the dataset.


Applies PCA for dimensionality reduction and species separation.


Highlights relationships between features (petal width, petal length, sepal width, sepal length).


#### • Walkthrough of Key Visuals

KPI Cards (Top) – Display averages for petal width, petal length, sepal width, and sepal length across species.


Table (Top Left) – Aggregates total sepal length and width per species.


Donut Chart (Top Middle) – Shows count and proportion of clusters.


Bar Chart (Bottom Left) – Compares average petal width, petal length, and sepal length by species.


Scatter Plot (Bottom Right) – PCA visualization (PC1 vs. PC2) showing species separation and cluster grouping.


Cluster vs. Petal Width Visual (Middle Right) – Highlights average petal width per cluster to explore clustering behavior.


#### • Business Impact & Insights

🌸 Biological Insights – Clear visualization of how petal and sepal dimensions differ by species.


📊 Cluster Analysis – Clusters provide an unsupervised perspective, showing grouping patterns beyond labels.


🧠 PCA Impact – Reduces complexity and reveals strong separation between species in 2D space.


🎓 Educational Use – Acts as an excellent teaching and demonstration tool for machine learning concepts.


🔍 Decision Support – Can be extended to other classification or clustering tasks as a reusable Power BI model.


## 6. Screenshot
