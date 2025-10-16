# 🛌 Student Sleep Pattern Analysis

[![Project Status](https://img.shields.io/badge/Status-Completed-success)](https://github.com/Oenm176/sleep-pattern-analysis)
[![Run on Deepnote](https://img.shields.io/badge/Run%20on%20Deepnote-FF5722?style=flat&logo=jupyter&logoColor=white)](https://deepnote.com/workspace/Catyos-6c14d7d6-5b23-4ffe-b677-43b144e918a9/project/Hartono-Adji-Susantos-Untitled-project-fa20d55e-eca4-4fa7-9a55-61597c94c97d/notebook/IDE-SleepPatternAnalysis-8cef5959ebb74b2bbea46c916d8d1162?utm_source=share-modal&utm_medium=product-shared-content&utm_campaign=notebook&utm_content=fa20d55e-eca4-4fa7-9a55-61597c94c97d)
[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/12fTNKJZwPUBJa4nA80HfLjnDU4ZkFxb0?usp=sharing)

This project presents an in-depth **Exploratory Data Analysis (EDA)** of student sleep duration. The analysis focuses on data quality checks, descriptive statistics, and visualization of the distribution to identify the primary sleep patterns within the sample.

***

## 🚀 How to Run the Analysis (Interactive)

The entire project can be run entirely **online** using one of the platforms below, ideal for *live demos* and code modification:

### Option 1: Deepnote (Primary Recommendation)
Click **"Run on Deepnote"** above to launch the integrated cloud VS Code environment.

### Option 2: Google Colab
Click **"Open in Colab"** above to run the notebook in the standard Google Colab environment.

***

## 📊 Project Structure

| File/Folder | Description |
| :--- | :--- |
| `data_cleansing.ipynb` | Notebook containing data quality checks, calculations for Mean, Median, Skewness, and Kurtosis. |
| `data_visualization.ipynb` | Notebook containing the main visualizations (Histogram, Dot Plot, Stem-and-Leaf Plot) for the EDA. |
| `Data/sleep_duration.csv` | The raw dataset used for the analysis. |
| `requirements.txt` | List of necessary Python libraries to reproduce the environment. |

***

## 💡 Key Findings (Final Insights)

The analysis of the sleep duration data indicates a healthy, near-normal distribution:

* **Data Quality:** The data is classified as **Clean**; no missing values, duplicates, or *outliers* were found using the Interquartile Range (IQR) method.
* **Central Tendency:** The mean sleep duration is $\mathbf{6.99 \text{ hours}}$ (Median: $7.05 \text{ hours}$), indicating the sample tends to sleep slightly below the recommended minimum of $7 \text{ hours}$.
* **Skewness (Symmetry):** The Skewness value ($\approx -0.05$) is very close to zero, suggesting the sleep duration distribution is **nearly Symmetrical** (no significant skew).
* **Kurtosis (Peakedness):** The Kurtosis value ($\approx -0.27$) technically classifies the distribution as **Platykurtic** (flatter peak), but visually, it closely resembles a normal distribution.

***

## 🛠 Technology Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy.stats, Tabulate
* **Interactive Platforms:** Deepnote & Google Colab

***

## 🤝 Contributor
* **Ibrahim Ahmad Adz Dzakwan** - 5241811006
* **Nyoman Arya Kristian Penny Karna Jaya** - 5241811013
* **Hartono Adji Susanto** - 5241811018
* **Azhara Kumala Dewi** - 5241811019



