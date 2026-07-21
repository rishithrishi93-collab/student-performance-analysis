# Student Performance Analysis

Python-based EDA and machine learning project analyzing how demographic 
and background factors relate to student exam performance, using a 
1,000-student dataset (math, reading, and writing scores).

## 🔗 Notebook

[View Full Analysis Notebook](student_performance_analysis.ipynb)

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Decision Tree Classifier)

## Key Insights

- Students who completed the test preparation course scored 5-10 points 
  higher on average across all three subjects, with the largest gap in writing (+9.9 points)
- Lunch type (a proxy for socioeconomic background) was the single strongest 
  predictor of passing, followed closely by test preparation course completion
- Parental education level had minimal predictive power once lunch type 
  and test prep were accounted for
- A Decision Tree classifier trained on background factors alone 
  (no scores) achieved 66% accuracy in predicting pass/fail — well above 
  the majority-class baseline, showing background factors carry real 
  but partial predictive signal

## Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 67% |
| Decision Tree (max depth 3) | 66% |

## Dataset

[Students Performance in Exams — Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
