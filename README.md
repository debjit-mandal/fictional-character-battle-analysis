
# Fictional Character Battle Outcome Analysis

## Overview
This repository contains an in-depth analysis of a fictional character battle dataset. The dataset includes attributes of various fictional characters from Marvel and DC Comics, such as strength, speed, intelligence, special abilities, and weaknesses. The goal is to predict the outcome of battles between these characters based on these features.

## Dataset Description
The dataset consists of the following columns:
- **Character**: Name of the fictional character.
- **Universe**: Universe or franchise from which the character originates.
- **Strength**: Physical strength on a scale from 1 to 10.
- **Speed**: Speed or agility on a scale from 1 to 10.
- **Intelligence**: Intelligence or strategic thinking on a scale from 1 to 10.
- **Special Abilities**: Special powers or abilities possessed by the character.
- **Weaknesses**: Vulnerabilities or weaknesses of the character.
- **Battle Outcome**: Binary variable indicating the outcome of the battle (1 for a win, 0 for a loss).

The dataset can be found in **Kaggle:** [🦸 Fictional Character Battle Outcome Prediction](https://www.kaggle.com/datasets/rabieelkharoua/fictional-character-battle-outcome-prediction)

## Analysis Summary
The analysis performed in this notebook includes the following steps:

1. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables.
   - Standardized the features for better model performance.

2. **Predictive Modeling**:
   - Built and evaluated multiple machine learning models including Logistic Regression, Decision Tree, Random Forest, and XGBoost.
   - Evaluated the models using metrics like accuracy, precision, recall, and F1 score.

3. **Feature Importance Analysis**:
   - Identified the most significant attributes influencing battle outcomes using feature importance from the Random Forest model.

4. **Advanced Analysis**:
   - Conducted correlation analysis to understand the relationship between different attributes.
   - Performed hyperparameter tuning using GridSearchCV to improve model performance.
   - Compared the performance of different models using a bar plot.

5. **Summary and Conclusion**:
   - Summarized the key findings and highlighted the best-performing model and significant attributes.

## Getting Started
To get started with the analysis, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/debjit-mandal/fictional-character-battle-analysis.git
   cd fictional-character-battle-analysis
   ```

2. **Install Dependencies**:
   - Ensure you have Python installed.
   - Install the required Python libraries using `pip`:
     ```sh
     pip install pandas numpy matplotlib seaborn scikit-learn xgboost
     ```

3. **Open the Notebook**:
   - Open the Jupyter Notebook to explore the analysis:
     ```sh
     jupyter notebook fictional_character_battle_analysis.ipynb
     ```

## Files in the Repository
- `fictional_character_battle_analysis.ipynb`: Jupyter Notebook containing the advanced analysis of the fictional character battle dataset.
- `fictional_character_battles_analysis.csv`: The dataset used for the analysis.

## Conclusion
This analysis provides a comprehensive approach to understanding the dynamics of fictional character battles and highlights the importance of various attributes in determining the outcomes. The Random Forest model, after hyperparameter tuning, emerged as the best model for predicting battle outcomes.

## License
This project is licensed under the MIT License.

## Acknowledgements
- The dataset was created for educational purposes to demonstrate data science techniques.
- Special thanks to the creators of the fictional characters from Marvel and DC Comics.