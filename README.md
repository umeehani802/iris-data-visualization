# iris-data-visualization
Explore and visualize the Iris flower dataset.
# 🌸 Exploring and Visualizing the Iris Dataset

## 📌 Objective
The main goal of this task is to understand how to:
- Load a dataset using Python
- Perform basic data inspection and summarization
- Create visualizations to explore patterns and relationships within the data

## 📂 Dataset
We used the **Iris flower dataset**, a classic dataset included with Seaborn. It contains 150 samples of iris flowers from three different species — Setosa, Versicolor, and Virginica — with features such as sepal length/width and petal length/width.

## 🧠 Approach
- The dataset was loaded using `sns.load_dataset("iris")`
- Data inspection was performed using `.head()`, `.info()`, and `.describe()`
- Visualizations were created using **Seaborn** and **Matplotlib**, including:
  - Boxplots to show distribution of features by species
  - Species-wise comparisons for petal and sepal dimensions

## 📊 Results and Insights
- **Petal features** are more informative for distinguishing between species than sepal features.
- **Setosa** is clearly separable from the other two species based on all features.
- Some **outliers** exist, especially in sepal width for Setosa.
- The dataset is **clean, balanced**, and well-suited for classification tasks.

## 📁 Files Included
- `iris_exploration.ipynb`: Jupyter Notebook with full code and analysis

## ✅ Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

Feel free to fork or clone this repository and run the notebook to explore the Iris dataset yourself!
