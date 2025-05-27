### 🟩 *Slide 1: Title Slide*

*Smart Crop Recommendation System*
Group 04 — Machine Learning-Based Solution
*Technologies:* Python · Scikit-learn · Seaborn · Pandas
*Presented by:* \[Your Name]

---

### 🟩 *Slide 2: Problem Statement*

🌾 *The Challenge:*
Farmers struggle to choose the most suitable crop under varying soil and weather conditions, resulting in poor yield.

🧠 *The Need:*
Build a data-driven solution to recommend the best crop based on real-time and historical environmental data.

---

### 🟩 *Slide 3: Objective*

🎯 *Purpose of the Project:*

* Predict the most suitable crop based on soil and climatic features
* Automate agricultural decision-making using classification models
* Visualize and evaluate model performance for accuracy and reliability

---

### 🟩 *Slide 4: Dataset & Preprocessing*

📂 *Dataset:* Crop_recommendation.csv

* *Features:* N, P, K, temperature, humidity, pH, rainfall
* *Target:* Crop label (22 classes)

🧼 *Preprocessing Steps:*

* Checked for nulls and duplicates
* Converted types as needed
* Feature selection & cleaning
* Normalization for scaling

---

### 🟩 *Slide 5: Graphs & Visuals — 1 (Feature Distributions)*

📊 *What we visualized:*

* 🔷 *Histograms* of N, P, K, temp, humidity, pH, rainfall
* 🔷 *Distplot* & *displot* of pH values
* 🔷 *Catplot* for rainfall distribution

🧠 *Insights:*

* Most features follow normal-like or skewed distributions
* Some clusters are visible, aiding classification

---

### 🟩 *Slide 6: Graphs & Visuals — 2 (Relationships)*

📊 *Plots Displayed:*

* 🔷 *Heatmap* showing correlations between features
* 🔷 *Pairplot* highlighting feature interactions
* 🔷 *Relplot* showing pH vs rainfall vs temp relationships

🧠 *Insight:*

* Temp, pH, and humidity show moderate-to-strong relationships with crop selection.

---

### 🟩 *Slide 7: Graphs & Visuals — 3 (Model Visualization)*

📊 *Model Evaluation Graphs:*

* 🔷 *Bar Plot* comparing model accuracies
* 🔷 *Decision Tree Plot* showing feature splits

🧠 *Conclusion:*

* Random Forest performs best (\~99%)
* Decision Tree helps interpret feature importance

---

### 🟩 *Slide 8: Algorithms Used*

🤖 *Models Implemented:*

| Algorithm           | Concept                       | Accuracy |
| ------------------- | ----------------------------- | -------- |
| Logistic Regression | Linear classifier             | \~94%    |
| K-Nearest Neighbors | Distance-based classification | \~98%    |
| Decision Tree       | Rule-based splits             | \~96%    |
| Random Forest       | Ensemble of trees             | \~99.5%  |

📍 All models trained/tested using *train\_test\_split* from Scikit-learn

---

### 🟩 *Slide 9: Evaluation & Comparison*

📈 *Metrics Used:*

* Accuracy Score
* Confusion Matrix
* F1 Score (implicit through model comparison)

🧪 *Outcome:*

* ✅ Random Forest gives highest accuracy
* ✅ Models show minimal overfitting
* ✅ Predictions match ground truth well

---

### 🟩 *Slide 10: Conclusion*

🌱 *Closing Thoughts:*
This system integrates data science with agriculture, offering a smart way to recommend crops using machine learning models trained on real soil and climate data.

💡 “From soil to solution — AI-driven agriculture begins here.”

---
