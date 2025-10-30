# Clean-Health-Data

## 📄 Project Description

This repository is dedicated to the process of **cleaning, merging, and preparing raw health-related datasets** for subsequent analysis or modeling. The core objective is to take disparate data sources—user profiles, health metrics, supplement usage, and experiment results—and transform them into a single, cohesive, and clean dataset (`merged_user_data.csv`).

The project uses a **Jupyter Notebook** to document and execute the entire data wrangling pipeline, ensuring reproducibility and clarity on all data cleaning and feature engineering steps.

---

## 📂 Repository Contents

The following files are contained within this repository:

| File Name | Description |
| :--- | :--- |
| `notebook.ipynb` | The primary **Jupyter Notebook** containing all Python code for data loading, cleaning, merging, and preliminary exploratory data analysis (EDA). |
| `user_profiles.csv` | Raw data file containing user demographic and profile information. |
| `user_health_data.csv` | Raw data file containing various recorded health metrics for users. |
| `supplement_usage.csv` | Raw data file detailing which supplements users are currently taking. |
| `experiments.csv` | Raw data file containing results or parameters from specific health experiments or trials. |
| `merged_user_data.csv` | The **final, cleaned, and merged** output dataset, ready for deep-dive analysis. |
| `schema.png` | A visual diagram illustrating the database or file relationships used in the data merging process. |

---

## 🚀 Getting Started

To explore the data cleaning process or run the analysis yourself, follow these steps:

### Prerequisites

You will need **Python** installed on your system, along with the following libraries (likely including the data science staples):

* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib** and **Seaborn** (for data visualization)

You can install the necessary dependencies using `pip`:

```bash
pip install pandas numpy matplotlib seaborn jupyter
