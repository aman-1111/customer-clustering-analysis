# 🧠 Customer Segmentation with PCA and KMeans

This project performs customer segmentation using unsupervised machine learning techniques. It applies preprocessing, dimensionality reduction (PCA), and KMeans clustering to uncover patterns in customer behavior.

## 📊 Features

- ✅ Handles missing values using imputation
- ✅ Scales data using `StandardScaler`
- ✅ Reduces dimensionality with `PCA`
- ✅ Segments customers using `KMeans` clustering
- ✅ Visualizes clusters in 2D using `matplotlib` and `seaborn`

## 📁 Dataset

The dataset used is `customer_data.csv`, which includes various customer-related features such as:

- Age
- Income
- Spending score
- ... (and more)

> _Note: Ensure your dataset is placed in the root directory as `customer_data.csv`._

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/customer-segmentation-pca.git
cd customer-segmentation-pca

    Install dependencies:

pip install -r requirements.txt

    Run the main script:

python customer_segmentation.py

    Results:

    Clustered data will be saved as customer_data_with_clusters.csv

    A PCA scatter plot of customer segments will be shown

🛠️ Requirements

    pandas

    numpy

    scikit-learn

    matplotlib

    seaborn

You can install all dependencies with:

pip install pandas numpy scikit-learn matplotlib seaborn

📈 Sample Output

<!-- Optional if you include a screenshot -->
🧠 Techniques Used

    Imputation: Filling missing values with column mean

    Standardization: Ensuring all features have zero mean and unit variance

    PCA: Reducing features to 2D for visualization

    KMeans: Grouping similar customers into clusters

📦 Output

    customer_data_with_clusters.csv: Data with cluster labels

    2D PCA plot showing customer segments

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
📄 License

MIT
📬 Contact

Made with ❤️ by Aman Chaurasia
