## Question 1 – KNN (Classification)

d(q, A) = √(2 - 1)² + (1 - 1)² = √1 = 1  

d(q, B) = √(2 - 2)² + (1 - 2)² = √1 = 1  

d(q, C) = √(2 - 4)² + (1 - 4)² = √13 = 3.6  

k = 2   

Predicted class: Dog, by majority.  

---

## Question 2 – Confusion Matrix (Open Question)  

 .  P   N  
 P| 8 | 3 |  
  |---|---|  
 N| 2 | 7 |  

---

## Question 3 – Hyperparameters  

D. Weights learned during model training - Is not a hyperparameter  

---

## Question 4 – Linear Regression Metrics  

Prediction for ŷ = 2x + 1:  
2 * 0 + 1 = 1  
2 * 1 + 1 = 3  
2 * 2 + 1 = 5  
2 * 3 + 1 = 7  

MSE = (1-1)² + (3-3)² + (5-5)² + (7-9)² =           4 / 4 =                1  
      Sum of squares                     Divided by number of samples    Answer  
  
SSE = (1-1)² + (3-3)² + (5-5)² + (7-9)² = 4  
SST = (1-4.5)² + (3-4.5)² + (5-4.5)² + (9-4.5)² = 20  
R² = 1 - 4 / 20 = 0.8  

Adjusted R² = 1 - (1 - 0.8) * ((4 - 1) / (4 - 1 - 1)) = 0.7  
  
MSE = 1  
R² = 0.8  
Adjusted R² = 0.7  

---

## Question 5 – Decision Tree (Classification)  

B. x ≤ 3  - Answer  

---

## Question 6 – Logistic Regression (Threshold)

f(x) = 1 / (1 + e^(-1)) = 0.731  
  
A logistic regression model is defined as:  
  
z = w₀x₀ + w₁x₁  
z = 2*1 + (-1)*1 = 1  
  
Where:  
  
* w₀ = 2  
* w₁ = -1  
* Threshold = 70%  
* Bias = 0  
  
For input x = (1,1)  
  
After applying the sigmoid function, determine whether the output is:  
B. Above the threshold - Answer is B  
  
---
  
## Question 7 – KNN (Regression)  
  
Euclidean distance:  
d(q, A) = √(2 - 1)² + (1 - 1)² = √1 = 1  
d(q, B) = √(2 - 2)² + (1 - 2)² = √1 = 1  
d(q, C) = √(2 - 4)² + (1 - 4)² = √13 = 3.6  
  
k = 2  
  
 Closest points: A and B  Devide by k=2  
Predicted value: (10 + 20)               / 2 =           15 - Answer  
  
---

## Question 8 – Confusion Matrix (Accuracy)  
  
Accuracy = (TP + TN) / (TP + TN + FP + FN)  
Accuracy = (3 + 5) / (3 + 5 + 1 + 2) = 0.8 - Answer  
  
---
  
## Question 9 – Overfitting  
  
B. Overfitting - Answer  
  
---
  
## Question 10 – SVM (Decision Surface)  
  
A linear SVM model is defined by:  
  
w₀x₀ + w₁x₁ + w₂x₂ + b = 0  
(1 * 2) + (-1 * 1) + (2 * 1) + (-3) = 0  
  
D. Cannot be determined  - Answer  
  
---
  
## Question 11 – Random Forest  
  
B. Error calculated using samples not selected in bootstrap sampling  - Answer  
  
---
  
## Question 12 – Elbow Method  
  
B. 2 - Answer  
  
---
  
## Question 13 – KNN (Distance Calculation)  
  
d(q, A) = √(2 - 1)² + (2 - 2)² + (2 - 1)² = √3 = 1.7  
  
d(q, B) = √(2 - 2)² + (2 - 0)² + (2 - 2)² = √5 = 2.2  
  
d(q, C) = √(2 - 3)² + (2 - 3)² + (2 - 0)² = √10 = 3.2  
  
d(q, D) = √(2 - 0)² + (2 - 1)² + (2 - 3)² = √6 = 2.4  
  
A, D, B Are the three nearest neighbors  
  
---
  
## Question 14 – MSE Calculation
  
MSE = (2-3)² + (4-5)² + (6-4)² = 2  
  
---
  
## Question 15 – Standard Deviation
  
x = [4, 7, 10, 10, 13, 15, 15, 18, 20, 28]  
  
μ = (4+7+10+10+13+15+15+18+20+28)/10 = 14  
  
σ = √((4-14)²+(7-14)²+(10-14)²+(10-14)²+(13-14)²+(15-14)²+(15-14)²+(18-14)²+(20-14)²+(28-14)²)/10) = 6.5  
  
STD = 6.5  
  
---
  
## Question 16 – Supervised Learning
  
C. The data includes input features and known output labels - Answer  
  
---
  
## Question 17 – Regression vs Classification  
  
B. Regression predicts continuous values while classification predicts discrete classes  - Answer  
  
---
  
## Question 18 – Regression Tree (Final Leaf MSE: Weighted vs Unweighted)   
  
Group A:  
5 * 2 = 10  
Group B:  
4 * 8 = 32  
  
MSE = (10 + 32) / (2 + 8) = 4.2 - Answer  
  
---
  
## Question 19 – Train vs Test  
  
C. Training is used to learn model parameters, test is used to evaluate performance on unseen data  - Answer  
  
---
  
## Question 20 – Random Forest Tasks
  
C. Both classification and regression  - Answer  
  
---
  
## Question 21 – Decision Tree (Regression)  
  
**B)**  
  
```  
[  
 1   4   16  
 1   8   64
 1  10  100
]
```  
Because the degree is 2 it gives back 3 columns.  
  
---
  
## Question 22 – Decision Tree (Regression)
  
B. Increases model complexity and risk of overfitting - Answer  

---
  
## Question 23 - Adjusted R²
  
**C)** Adjusted R² ignores the number of features and only measures error  - Answer  
  
---
  
## Question 24 – Logistic Regression Output  
  
C. A probability estimate  - Answer  
  
--- 
  
## Question 25 – Evaluation Metric
  
B. Accuracy  - Answer  
  

