# Cryptocurrency Staking Database and Analysis

This repository contains the Jupyter notebook and related materials for my master's thesis titled **"Cryptocurrency Staking Database and Analysis."** The notebook provides an in-depth analysis of staking mechanisms, particularly focusing on Tezos (XTZ), and explores various factors influencing the performance and rewards of Tezos bakers.

## Purpose

The primary purpose of this notebook is to analyze the performance and behavior of bakers within the Tezos blockchain network. The analysis involves:

- Creating a comprehensive database of Tezos bakers.
- Performing Exploratory Data Analysis (EDA) to identify key trends and relationships.
- Evaluating the staking offers and reliability of different bakers.
- Analyzing the delegation capacity and network share of bakers across multiple cycles.
- Providing insights and recommendations based on the analysis.

## Notebook Contents

### 1. **Introduction**
   - Overview of the cryptocurrency staking process.
   - Introduction to Tezos and its staking mechanisms.

### 2. **Data Collection and Preparation**
   - Description of the datasets used (`merged_baker_files.csv`, `merged_cycle_files.csv`).
   - Data cleaning and preprocessing steps.
   - **[Access the Dataset](https://drive.google.com/drive/folders/1njc2F8vt3D2AXB6EGL9EESDoUgj585at)**: The datasets used in this analysis can be accessed via this Google Drive link.

### 3. **Exploratory Data Analysis (EDA)**
   - Analysis of baker staking fees and KDE plot.
   - Correlation matrix analysis to identify relationships between different metrics.
   - Detailed analysis of delegation capacity vs. network share.
   - Violin plot of baker reliability scores.
   - Bakers' participation summary across different cycles.
   - Time-series analysis of delegation capacity for the top 10 bakers.

### 4. **Results and Findings**
   - Key insights derived from the analysis.
   - Comparative analysis of baker performance.
   - Discussion on the implications of the findings for stakeholders in the cryptocurrency ecosystem.

### 5. **Conclusion**
   - Summary of the research and analysis.
   - Recommendations for future work and further analysis.

## How to Use the Notebook

1. **Clone the Repository:**
   - Clone this repository to your local machine using the following command:
     ```bash
     git clone https://github.com/yourusername/cryptocurrency-staking-analysis.git
     ```

2. **Install Dependencies:**
   - Ensure that you have Python installed on your system.
   - Install the required Python packages using:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Notebook:**
   - Open the Jupyter notebook in your local environment:
     ```bash
     jupyter notebook Cryptocurrency_Staking_Analysis.ipynb
     ```
   - Follow the cells sequentially to reproduce the analysis.

4. **Explore the Data:**
   - You can modify the analysis, add new plots, or explore different aspects of the data by editing the notebook cells.

5. **Results Interpretation:**
   - The notebook includes detailed explanations and visualizations that guide you through the analysis process. Use the provided insights to understand the dynamics of Tezos staking.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn (Python libraries)

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or suggestions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or further information, please contact [Ridwan Ibidunni] at [Ridwan.IBIDUNNI2um6p.ma].

---

This README file now includes a direct link to your Google Drive folder containing the datasets.
