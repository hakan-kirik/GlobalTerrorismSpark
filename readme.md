# Global Terrorism Data Analysis and Modeling

This project demonstrates the analysis and modeling of the Global Terrorism Database using Python libraries such as **PySpark**, **Pandas**, and **Matplotlib**. The notebook explores data processing, visualization, and predictive modeling techniques to derive insights and predict the success of terrorism events.

---

## Features

- **Data Analysis**
  - Average kills by group
  - Total wounded by country
  - Total casualties by city
  - Average wounded by region
  - Analysis of chemical weapon usage
  - Total kills by target types
- **Predictive Modeling**
  - Random Forest Classifier with an accuracy of **77.67%**
  - Data preprocessing, including handling missing data and oversampling for class balancing
- **Visualization**
  - Bar charts for key metrics
  - Confusion matrix for model evaluation
  - Feature importance chart

---

## Technologies Used

- **PySpark**: For handling large datasets and distributed processing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating informative visualizations.
- **Machine Learning**: Random Forest Classifier for predictive modeling.

---

## How to Run the Project

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/hakan-kirik/GlobalTerrorismSpark
   ```
2. Install the required Python libraries:
   ```bash
   pip install pyspark pandas matplotlib scikit-learn
   ```
3. Download the dataset (`https://www.kaggle.com/datasets/START-UMD/gtd`) and rename 'globalterrorismdb.csv' is in the same project directory.
4. Open the Jupyter Notebook and run the cells sequentially:
   ```bash
   jupyter notebook
   ```
5. Follow the outputs and visualizations for insights.

---

## Insights and Results

1. **Top Groups by Average Kills**:
   - Identified the groups with the highest average kills per attack.

2. **Countries with the Highest Total Wounded**:
   - Highlighted countries most affected by terrorism based on casualties.

3. **Cities with the Highest Casualties**:
   - Analyzed the cities suffering the most from terrorist activities.

4. **Chemical Weapon Usage**:
   - Investigated groups using chemical weapons.

5. **Predictive Modeling**:
   - Achieved an accuracy of **77.67%** using a Random Forest Classifier.

---

## Visualization Samples

- **Bar charts**: Average kills by group, total wounded by country.
- **Feature Importance**: Displayed the contribution of features to the prediction model.
- **Confusion Matrix**: Showed the accuracy and precision of the classification model.

---

## Conclusion

This project provides a comprehensive workflow for analyzing and modeling terrorism data. By leveraging PySpark for big data handling and Random Forest for predictive modeling, it delivers actionable insights into global terrorism trends.
