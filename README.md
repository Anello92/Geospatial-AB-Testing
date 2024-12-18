# 📊 **Geospatial A/B Testing Analysis**

Welcome to the **Geospatial A/B Testing Analysis** repository! This project demonstrates a robust workflow for analyzing A/B test results in marketing campaigns with geospatial data, using Python.

---

## 📋 **Overview**

In this project, we:

1. Analyze geospatial data from an A/B marketing campaign.
2. Validate assumptions using statistical tests (Shapiro-Wilk, Levene).
3. Apply statistical methods (T-test, Mann-Whitney U) to assess conversion rates.
4. Visualize results with insightful plots.

---

## 🗂️ **Repository Structure**

- **`ab_test_analysis-2.ipynb`**: Notebook containing the detailed analysis workflow.
- **`dataset.csv`**: Dataset used for the analysis.

---

## 🛠️ **Tools & Technologies**

- **Python Libraries**:
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for data visualization.
  - `scipy` for statistical tests.
- **Notebook Features**:
  - Markdown for documentation.
  - Inline comments for clear explanations.

---

## 🔍 **Dataset Overview**

| Column       | Description                              |
|--------------|------------------------------------------|
| `user_id`    | Unique user identifier                   |
| `group`      | Experiment group (A or B)                |
| `latitude`   | User's geographic latitude               |
| `longitude`  | User's geographic longitude              |
| `conversion` | Conversion indicator (1=Yes, 0=No)       |

---

## 🚀 **Getting Started**

1. Clone the repository:
   ```bash
   git clone https://github.com/Anello92/Geospatial-AB-Testing.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Geospatial-AB-Testing
   ```

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:
   ```bash
   jupyter notebook ab_test_analysis-2.ipynb
   ```

---

## 📈 **Results**

- **Statistical Insights**:
  - Normality and homogeneity tests.
  - Significant differences in conversion rates between groups.
- **Visualizations**:
  - Geospatial distributions of conversions.
  - Comparative plots for group performance.

---

## 🎯 **Key Learnings**

This project highlights the importance of:
- Rigorous statistical validation for A/B testing.
- Clear communication of findings using visuals.
- Handling and analyzing geospatial data effectively.

---

## 🤝 **Contributing**

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

---

## ✨ **Acknowledgements**

Thanks to all contributors and the open-source community for their invaluable tools and resources.

---

Made with ❤️.

