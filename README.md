# OnlineGamingBehaviorPrediction
Machine Learning project predicting player behavior in online games.

🎯 Overview :

This project applies supervised machine learning techniques to predict the engagement level of online gamers — classified as Low, Medium, or High — using demographic, behavioral, and psychological features. It also attempts to predict in-game purchase behavior. The goal is to help gaming companies improve user retention, personalization, and monetization strategies

🧠 Data Overview :
	•	Source: Kaggle
	•	Size: 40,034 player records
	•	Features: 13 predictors (demographics, gameplay behavior) + 2 target variables:
	•	EngagementLevel: 0 = Low, 1 = Medium, 2 = High
	•	InGamePurchase: 0 = No, 1 = Yes
🛠️ ML Pipeline :

📌 Preprocessing :
	•	Label encoding & one-hot encoding for categorical features
	•	StandardScaler for numerical normalization
	•	No missing values found

📈 Models Used :
	•	Random Forest
	•	Gradient Boosting (best for engagement)
	•	Logistic Regression
	•	Support Vector Classifier (SVC)
 
 ✅ Results :

Engagement Level Prediction :
	•	Best Model: Gradient Boosting
	•	Accuracy: 91.77%
	•	Insights: Most accurate for Medium class; minor confusion between Low & High.

In-Game Purchase Prediction :
	•	Best Model: Random Forest
	•	Accuracy: 79.92%
	•	Issue: Severe class imbalance → 0% precision/recall for purchase class

📊 Project Highlights :
	•	Multi-class classification of player engagement
	•	Binary classification of in-game purchases
	•	Gradient Boosting achieved 91.77% accuracy on engagement prediction
	•	In-game purchase prediction faced challenges due to class imbalance
	•	Future improvements suggested using SMOTE and class rebalancing
