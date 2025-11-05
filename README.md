# 🧠 EDA-Projects

This repository showcases multiple **Exploratory Data Analysis (EDA)** projects demonstrating how to explore, visualize, and interpret datasets effectively.  
Each project walks through data cleaning, feature understanding, visualization, and reporting — forming a strong foundation for data-driven decision-making.

---

## 📊 Overview

Exploratory Data Analysis (EDA) helps uncover patterns, spot anomalies, and test hypotheses using data visualization and statistical summaries.  
These projects aim to:
- Perform in-depth data exploration using **Python**.
- Build meaningful and interactive visualizations.
- Automate EDA reporting.
- Manage reproducible workflows with **DVC** and **Conda**.

---

## ⚙️ Technologies Used

| Category | Tool / Library | Purpose |
|-----------|----------------|----------|
| **🧠 Language** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Main programming language |
| **📊 Data Analysis** | ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) | Data manipulation and computation |
| **📈 Visualization** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white) | Static and interactive data visualizations |
| **🤖 Automated EDA** | ![Pandas Profiling](https://img.shields.io/badge/Pandas%20Profiling-0A0A0A?logo=pandas&logoColor=white) | Auto-generate summary EDA reports |
| **⚙️ Environment Management** | ![Conda](https://img.shields.io/badge/Conda-44A833?logo=anaconda&logoColor=white) | Handles dependencies and reproducible environments |
| **🧩 Data Versioning** | ![DVC](https://img.shields.io/badge/DVC-945DD6?logo=dvc&logoColor=white) | Tracks datasets and pipeline versions |
| **💻 Notebook Sharing** | ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white) | Open `.ipynb` notebooks publicly in the cloud |
| **🗂️ Configuration** | ![YAML](https://img.shields.io/badge/YAML-000000?logo=yaml&logoColor=white) | Used for environment setup and DVC pipelines |
| **🔧 Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) | Source code and version management |

---

## 🧩 Project Structure

```bash
EDA-projects/
│
├── 📁 netflix-eda/
│   ├── data/                # Raw and processed datasets
│   ├── notebooks/           # Jupyter notebooks for EDA
│   ├── visuals/             # Saved plots and charts
│   ├── dvc.yaml             # DVC pipeline for data workflow
│   ├── params.yaml          # Pipeline configuration parameters
│   └── README.md
│
├── 📁 youtube-eda/
│   ├── data/
│   ├── notebooks/
│   ├── visuals/
│   ├── dvc.yaml
│   ├── params.yaml
│   └── README.md
│
├── 📁 zomato-eda/
│   ├── data/
│   ├── notebooks/
│   ├── visuals/
│   ├── dvc.yaml
│   ├── params.yaml
│   └── README.md
│
├── environment.yml          # Conda environment setup file
├── requirements.txt         # Python package list (for pip users)
├── .dvc/                    # DVC tracking folder
├── .gitignore               # Ignore unnecessary files
└── README.md                # Main documentation
