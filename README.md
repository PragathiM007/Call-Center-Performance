# Call Center Performance Analysis

📌 **Project Overview**

This project analyzes call center operational data to understand key performance metrics such as call volume, abandonment rates, wait times, and service levels. Using data cleaning, feature engineering, regression modeling, classification, and statistical testing, it identifies factors influencing call abandonment and overall service quality.

📊 **Dataset**

- **Source:** Internal call center records (1,251 records)  
- **Size:** 1,251 entries  
- **Features:**  
  - Incoming Calls  
  - Answered Calls  
  - Answer Rate (%)  
  - Abandoned Calls  
  - Answer Speed (AVG) (minutes)  
  - Talk Duration (AVG) (minutes)  
  - Waiting Time (AVG) (minutes)  
  - Service Level (20 Seconds) (%)  

🎯 **Objectives**

- Clean and preprocess call center data for analysis  
- Convert time-based metrics into numeric formats for modeling  
- Explore relationships between call center metrics through correlation and regression  
- Build predictive models to estimate call abandonment using Ridge Regression and Random Forest  
- Perform statistical testing to validate operational hypotheses  
- Visualize performance patterns and segment data via clustering  

🧠 **Machine Learning Models Used**

- Ridge Regression  
- Random Forest Classifier  

📈 **Performance Metrics**

- Ridge Regression achieved an R² of approximately 1.0 and a near-zero RMSE, indicating excellent fit to abandonment data.  
- Random Forest classification attained 98% accuracy in predicting high abandonment scenarios, with strong precision and reasonable recall.  

🧪 **Preprocessing Steps**

- Conversion of time string columns into float minutes  
- Removal of percentage signs and conversion to float for rate metrics  
- Handling missing values with median imputation  
- Creation of rolling averages and call volume categories for enhanced analysis  

📊 **Visualizations**

- Histograms and violin plots to understand metric distributions  
- Correlation heatmaps to reveal relationships between features  
- Scatter plots and clustering to identify operational groups  
- Residual analysis to evaluate model fit  

📁 **Folder Structure**

call-center-performance-analysis/  
├── data/  
│   └── call_center_data.csv  
├── notebooks/  
│   └── call_center_analysis.ipynb  
├── models/  
│   └── ridge_regression_model.pkl  
├── outputs/  
│   ├── visuals/  
│   └── reports/  
├── README.md  

🧠 **Key Learnings**

- Call abandonment strongly correlates with waiting times and call volumes.  
- Effective predictive models can guide operational decisions to reduce abandonment.  
- Statistical testing confirms significant differences in abandonment between low and high call volumes.  
- Clustering reveals distinct operational profiles, enabling targeted resource allocation.  

🔮 **Future Enhancements**

- Incorporate timestamped call data for temporal trend analysis  
- Integrate staffing and shift schedules for more comprehensive modeling  
- Develop real-time dashboards for monitoring and alerts  
- Experiment with advanced machine learning models (e.g., XGBoost, deep learning)  

👤 **Author**

Pragathi Porawakara Arachchige  
[GitHub](https://github.com/pragathim007) | [Portfolio](https://pragathim007.github.io/pragathi-portfolio/)

📜 **License**

This project is licensed under the PAPM License.
