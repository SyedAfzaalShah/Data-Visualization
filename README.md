# Data Visualization

A data visualization project using the classic Iris dataset. The project explores the relationships and distributions of flower features across three species using Scatter Plots, Histograms, and Box Plots built with Matplotlib and Seaborn.

---

## Project Overview

The Iris dataset is one of the most well-known datasets in data science. This project focuses purely on visualizing the dataset to uncover patterns and differences between the three iris species — Setosa, Versicolor, and Virginica — across four measured features.

---

## Project Structure

```
Data-Visualization/
│
├── data_visualization.ipynb   # Main Jupyter Notebook
└── README.md
```

---

## Dataset

**Source:** Built-in Iris dataset loaded directly via Seaborn (`sns.load_dataset('iris')`)

No external CSV file is needed. The dataset is loaded automatically.

| Feature | Description |
|---|---|
| sepal_length | Length of the sepal in cm |
| sepal_width | Width of the sepal in cm |
| petal_length | Length of the petal in cm |
| petal_width | Width of the petal in cm |
| species | Iris species — Setosa, Versicolor, Virginica |

**Shape:** 150 rows and 5 columns

---

## Visualizations

**Scatter Plots**

- Petal Length vs Petal Width colored by species
- Sepal Length vs Sepal Width colored by species

**Histograms**

- Distribution of Sepal Length
- Distribution of Sepal Width
- Distribution of Petal Length
- Distribution of Petal Width

**Box Plots**

- Sepal Length by Species
- Sepal Width by Species
- Petal Length by Species
- Petal Width by Species

---

## Tech Stack

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Getting Started

**1. Clone the Repository**

```bash
git clone https://github.com/SyedAfzaalShah/Data-Visualization.git
```

**2. Install Dependencies**

```bash
pip install pandas numpy matplotlib seaborn
```

**3. Run the Notebook**

```bash
jupyter notebook data_visualization.ipynb
```

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
