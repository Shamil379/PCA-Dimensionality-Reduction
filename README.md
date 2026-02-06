# PCA-Dimensionality-Reduction

📊 Dataset

Source: sklearn.datasets.load_digits() (MNIST-like handwritten digits)

Images are flattened into feature vectors

Target: Digit classes (0–9)

⚙️ Methodology

Load and flatten digit images

Normalize features using StandardScaler

Apply PCA with multiple component values (2, 10, 30, 50)

Track and plot cumulative explained variance

Reduce dataset using optimal PCA components

Train Logistic Regression on:

Original dataset

PCA-reduced dataset

Compare classification accuracy

Visualize data using 2D PCA scatter plot

📈 Results

PCA significantly reduces dimensionality with minimal accuracy loss

30 PCA components retain most of the variance

PCA improves training efficiency while maintaining performance

🛠 Tools & Libraries

Python, NumPy, Pandas, Matplotlib

Scikit-learn

▶️ How to Run

Open the notebook

Run all cells sequentially

Outputs and files are generated automatically
