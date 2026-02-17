# BUSINESS PROBLEM: 
The telecom company wants to reduce customer churn and prevent revenue loss by identifying customers who are likely to leave. By predicting which customers are at risk of churning, the company can apply targeted retention strategies, such as personalized offers or engagement campaigns, to keep them.

# OBJECTIVE: Minimize customer churn and revenue loss

# Data Exploration
	•	Examined customer demographics, usage patterns, and service features.
	•	Identified influential features eg customer service calls, total day charges, and international plan subscription.
# Data Preprocessing
	•	Handled missing values and categorical variables.
	•	Applied SMOTE to balance the imbalanced dataset (116 churners vs 551 non-churners).
# Model Building
	•	Settled on Decision Tree Classifier to predict churn after trying logistic regression
	•	Focused on maximizing churner recall to catch as many potential churners as possible.
# Evaluation
	•	Confusion matrix, precision, recall, F1-score, and accuracy were used.
	•	Achieved 88% accuracy with strong recall for churners (77%), providing actionable insights for retention.
# Recommendations
	•	Target predicted churners with personalized retention strategies.
	•	Continuously monitor flagged customers and update the model with new data.

# BUSINESS INSIGHTS
497 OUT OF 551 NON-CHURNERS WERE CORRECTLY PREDICTED, HENCE A 90% RETENTION AMONG CUSTOMERS. FOCUSING ON LOYALTY PROGRAMS AND REWARDS WOULD MAINTAIN STRONG RETENTION

27 CHURNERS PREDICTED AS NONCHURNERS COULD SLIP THROUGH UNNOTICED HENCE, IMPLEMENTATION OF RISK-BASED INTERVENTIONS FOR CUSTOMERS WITH BODERLINE SCORES WOULD REDUCE MISSED CHURN OPPORTUNITIES.

[CHECKOUT THE PROJECT PRESENTATION](https://www.canva.com/design/DAHBla_ADXQ/wsRt6C-o8nmTwwxMLgViSw/view?utm_content=DAHBla_ADXQ&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hafd4ab179c)



