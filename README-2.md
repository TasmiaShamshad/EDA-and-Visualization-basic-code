# 🏡 Listings Dataset Analysis

## 📊 Overview

This project is a data analysis exercise using a listings dataset (such as from Airbnb). It includes steps for cleaning missing values, dropping duplicates, converting date formats, and visualizing various aspects of the data such as:

- Room types
- Neighborhoods
- Price distributions
- Review patterns
- Correlation between numerical variables

---

## 📁 Files Included

- `Task-1_DS.ipynb`: Jupyter Notebook containing the full code for data cleaning, exploration, and visualization.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧼 Data Cleaning Steps

- Converted `last_review` to datetime format.
- Dropped rows with null values in critical columns (`last_review`, `name`).
- Removed duplicate entries.
- Reset DataFrame index after cleaning.

---

## 📈 Visualizations

The notebook includes the following plots:

- **Countplot of Room Types**
- **Countplot of Neighbourhood Groups**
- **Neighbourhood Distribution**
- **Histograms** for:
  - Price
  - Minimum nights
  - Number of reviews
- **Correlation Heatmap** of numeric features

---

## 📚 Key Insights

- Distribution of listing types across neighborhoods
- Common room types and their frequency
- Relationships between price, reviews, and other numeric features

---

## 🚀 How to Run

1. Clone the repository.
2. Open the notebook in Jupyter Notebook or any compatible environment.
3. Ensure you have the required CSV file (`listings.csv`) in the correct path or update the path accordingly.
4. Run all cells sequentially to view the output.

---

## 📬 Contact

For questions or collaboration, feel free to open an issue or connect via GitHub.

---

## 🔖 License

This project is open-source and free to use for learning and educational purposes.
