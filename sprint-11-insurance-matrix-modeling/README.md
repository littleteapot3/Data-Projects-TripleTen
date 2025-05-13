# Project: MatrixInsure
A linear algebra project for insurance analytics. 

## 📌 Overview  
This project is all about using **linear algebra and machine learning** to help **Sure Tomorrow Insurance** make smarter decisions. The company wants to:  
- Find similar customers for better marketing,  
- Predict who might receive insurance benefits,  
- Estimate how many benefits a customer could get, and  
- Keep customer data private without messing up predictions.  

By working through these challenges, we’re blending math, coding, and real-world problem-solving!  

## 🎯 Goals  
The main goal of this project is to **explore how linear algebra powers machine learning models** in practical scenarios. Along the way, we’ll:  
- Use **distance metrics** to group similar customers.  
- Train models to **predict insurance benefits** (and compare them to a random guess).  
- Build a **linear regression model** to estimate benefits.  
- Apply **data masking** to protect personal information—without breaking our model.  

## 📊 The Data  

The dataset (`insurance_us.csv`) contains:  
- **Features**: Gender, age, salary, and number of family members.  
- **Target**: Number of insurance benefits received in the last five years.  

## 🛠 How It Works  

### 🔍 Step 1: Exploratory Data Analysis (EDA)  
- Clean the data and check for missing values.  
- Creates data visualizations for key patterns with histograms, boxplots, and scatterplots.
- Examines relationships between features using a correlation matrix heatmap.
- Analyzes outliers in income and family members.

![image](https://github.com/user-attachments/assets/21dfa5c2-423d-4b44-afc2-e048f3a1656d)


### 🤖 Step 2: Build Machine Learning Models  
**Finding Similar Customers with k-Nearest Neighbors (kNN)**
We explored different ways to group similar customers based on their characteristics:

- Tried different feature combinations—comparing age & gender vs. income & family size.
- Tested Euclidean vs. Manhattan distances to see how similarity is measured.
- Looked at how scaling (MaxAbsScaler) changes the closest matches—turns out, scaling can totally reshuffle the ranking of nearest neighbors!

      <img width="553" alt="image" src="https://github.com/user-attachments/assets/61a3b5e3-c04a-4187-b2df-d9f16b8ee437" />


   
**Predicting Benefit Eligibility with Regression**
We built a linear regression model to estimate how many benefits a customer might receive.

- Next, we’ll improve accuracy by testing Ridge and Lasso regression to prevent overfitting.
- There is also a plan to visualize these predictions using scatterplots with regression lines to make the patterns clearer.



**Privacy Protection for Customer Data**
To ensure customer information stays secure, we experimented with data obfuscation techniques.

- The goal was to protect privacy while making sure our models still work accurately.
- We found that even after masking sensitive data, predictions remained reliable—a great result!


## 📈 Key Takeaways  

- **kNN clustering** successfully identified groups of similar customers.  
- **Predictive models** performed better than a random guess (which is always a good sign!).  
- **Linear regression** provided reasonable estimates for the number of benefits.  
- **Data masking** worked! We protected customer data without hurting accuracy.

## 🔦 Future Improvements

- Exploring alternative regression techniques (e.g., Ridge, Lasso).

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/project-MatrixInsure.git
   cd project-MatrixInsure

