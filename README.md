# Astronomical Tabular Data Visualization

This project focuses on visualizing astronomical data using Python. The primary goal is to analyze star data and create visual representations such as the **Hertzsprung-Russell (HR) diagram** and **pair plots** to identify patterns and relationships in the dataset.

## 📊 Project Overview

The notebook uses a publicly available star dataset to:
- Load and preprocess the data.
- Generate various visualizations including:
  - **Pair Plots** for understanding relationships between features.
  - **HR Diagrams** to categorize stars based on their luminosity and temperature.

---

## 📂 File Structure

- **Astronimical_tabular__data_visualization.ipynb**: Jupyter notebook containing the code for data visualization.
- **Data Source**: The dataset is hosted on Google Drive and directly loaded using pandas.

---

## 📜 Libraries Used
The following Python libraries are used in this project:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **seaborn**: For creating advanced visualizations like pair plots.
- **matplotlib**: For general-purpose plotting.

---

## 💾 Dataset Information
The dataset contains information about different stars with attributes like:
- **Temperature (K)**: Surface temperature of the star.
- **Luminosity (L/Lo)**: Luminosity relative to the Sun.
- **Radius (R/Ro)**: Radius relative to the Sun.
- **Star Type**: Classification of stars (e.g., Main Sequence, Giants, Dwarfs).
- **Color**: Apparent color of the star.

The dataset is directly imported using:
```python
star_df= pd.read_csv('https://drive.google.com/uc?id=1BQVc6MHjQFtDC9iP1isT_K4ojVe_Oil-')
```

---

## 📊 Visualizations Created
1. **Pair Plot**: A seaborn pair plot to visualize relationships between multiple features in the dataset.
2. **HR Diagram**: A Hertzsprung-Russell diagram to categorize stars based on their luminosity and temperature.
3. **Data Insights**: Quick data insights using `pandas.DataFrame.info()` and random sampling.

---

## 💻 How to Run the Project
1. Clone the repository or download the notebook file.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Run the cells in sequence to visualize the data.

---

## 📈 Results
The visualizations provide insights into the classification of stars and their physical properties. The HR diagram helps in identifying:
- **Main Sequence Stars**
- **Giants**
- **White Dwarfs**

The pair plot shows how different features correlate with each other, offering a broader perspective of the star data.

---

## ✅ Future Scope
- Enhance visualizations by adding 3D plots.
- Incorporate more datasets from official astronomical databases.
- Build a machine learning model to classify stars.

---

## 📬 Contact
For any questions or contributions, feel free to reach out.

---
