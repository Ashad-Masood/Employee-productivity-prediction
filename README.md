# Employee-productivity-prediction

##  Overview  
This project predicts the productivity of garment factory employees using machine learning techniques in **Python**.  
The goal was to understand how operational factors such as overtime, team size, department, and incentives influence overall team productivity.

It showcases a complete **data science workflow** — from cleaning raw data to building, testing, and interpreting models.



##  Key Features  
- Cleaned and prepared raw data using **Pandas** and **NumPy** (handled missing values, converted categorical features using dummy variables).  
- Conducted **exploratory data analysis (EDA)** to visualize patterns and correlations using **Matplotlib** and **Seaborn**.  
- Built and compared **Decision Tree** and **Random Forest** models using **Scikit-learn**.  
- Applied **10-fold cross-validation** for reliable performance testing.  
- Achieved **~85% accuracy** with the **Random Forest Classifier**.  
- Evaluated using **Precision (0.84)**, **Recall (0.82)**, and **F1-Score (0.83)**.  
- Visualized **confusion matrix** and **feature importance** to interpret which factors most influenced productivity.  



## Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook / Python scripts  



## Results & Insights  
- **Best Model:** Random Forest Classifier (85% Accuracy)  
- **Top Influential Features:** Overtime and incentive amounts had the strongest impact on productivity.  
- **Business Insight:** High incentive and moderate overtime improved productivity without increasing idle time.  
- Demonstrates a practical, end-to-end **machine learning pipeline** for real-world manufacturing data.


## How to Run  
```bash
# Clone this repository
git clone https://github.com/<your-username>/employee-productivity-ml.git

# Go to the project directory
cd employee-productivity-ml

# Install dependencies
pip install -r requirements.txt

# Run the script
python predicting_employee_productivity_ML.py
