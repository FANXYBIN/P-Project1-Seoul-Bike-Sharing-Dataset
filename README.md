# P-Project1-Seoul-Bike-Sharing-Dataset

This project applied machine learning models to the Seoul Bike Sharing dataset to predict rental demand based on weather and temporal conditions. The analysis aimed to help optimize bike distribution, adjust operations during weather changes, and identify seasonal rental trends.

* **Dataset:** Seoul Bike Sharing Demand Dataset (UCI Machine Learning Repository, 8760 rows × 14 features).  
* **Tools:** Python (pandas, scikit-learn, seaborn, matplotlib, statsmodels).  
* **Techniques:** Data preprocessing, visualization (histogram, scatterplot, line plot, correlation heatmap), and supervised learning (SVM, Gradient Boosting, Random Forest, and Multiple Linear Regression).  
* **Key Findings:**  
  - **Peak demand** at 8 AM and 6 PM (commuting hours).  
  - **Temperature (15 – 30 °C)** positively affects rentals; **rainfall, humidity, and wind speed** reduce them.  
  - **Summer** records the highest rental activity, followed by spring and autumn.  
* **Models Evaluated:**  
  - **SVM:** Accuracy = 78.99%, Precision = 77.67%, Recall = 78.99%, F1 = 77.93%.  
  - **Gradient Boosting:** Accuracy = 79.83%, F1 = 79.20%.  
  - **Random Forest:** Accuracy = 80.02%, F1 = 79.50%.  
  - **Multiple Linear Regression:** R² = 0.473, F-statistic = 609.8 (significant predictors: hour, temperature, humidity, rainfall).  
* **Insights & Recommendations:**  
  - Use forecasts to rebalance bikes before morning/evening peaks.  
  - Adjust staffing and offer promotions during poor-weather periods.  
  - Promote biking events in warm seasons to leverage natural demand growth.

---

### 📊 Sample Visualizations

**Hourly Rentals by Season**  
![Line Plot](images/seoul_lineplot_season.png)

**Correlation Heatmap**  
![Heatmap](images/seoul_heatmap.png)

**Model Performance Comparison**  
![Model Comparison](images/seoul_model_performance.png)


