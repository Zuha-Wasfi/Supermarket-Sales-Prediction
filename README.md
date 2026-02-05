# Supermarket-Sales-Prediction

## 📌 Project Overview
This project focuses on analyzing supermarket sales data (2020-2023) to forecast demand and minimize inventory loss. By integrating multiple datasets, we aim to provide actionable insights for better supply chain management.

## 📂 Repository Structure
- `Data/`: Contains raw datasets (Annex 1-4) and processed split files.
- `Data_Preprocessing.ipynb`: Data cleaning, merging, and partitioning.

## 🛠️ Data Preprocessing
I have performed the following:
- **Data Integration:** Merged 4 separate CSV files into a master dataset.
- **Cleaning:** Handled missing values using Forward Fill (ffill) and standardized date formats.
- **File Management:** Split the large master file into two parts to comply with GitHub's 100MB limit.
- **Portability:** Configured relative paths (`Data/`) for seamless team collaboration.

## 📊 Technical Highlights
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Logic:** Implemented `np.array_split` for efficient data handling.
