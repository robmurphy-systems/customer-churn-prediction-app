# customer-churn-prediction-app
End-to-end ML churn prediction app deployed on Hugging Face. Provides real-time inference, business-focused metrics, and a production-oriented design bridging data science and enterprise delivery.

**Customer Churn Prediction App**

**Overview**

This project predicts customer churn using machine learning and delivers the results through an interactive web application deployed on Hugging Face.

The goal is not just model accuracy—but enabling real-time, business-friendly decision support for customer retention strategies.

**Live Demo**

https://huggingface.co/spaces/bobasami/third

**Business Problem**

Customer churn directly impacts revenue and growth. Acquiring new customers is significantly more expensive than retaining existing ones.

**This application helps answer:**

1) Which customers are at risk of leaving?
2) What factors contribute most to churn?
3) How can teams proactively intervene?

**Tech Stack**

1) Python
2) Scikit-learn
3) Pandas / NumPy
4) Streamlit - for UI
5) Deployment: Hugging Face Spaces

**Model Details** 
1) Algorithm: Random Forest Classifier 
2) Target: Binary classification (Churn / No Churn)

**Key Metrics:**

Accuracy: XX%

Precision: XX%

Recall: XX%

Focus was placed on minimizing false negatives (i.e., customers predicted to stay but actually churn), as these represent missed retention opportunities.

**Application Features**
1) Interactive input for customer attributes
2) Real-time churn prediction
3) Probability scoring for risk assessment
4) Simple UI for non-technical user

6) Project Structure
customer-churn-prediction-app/
│
├── app.py
├── model/
├── data/
├── notebook/
├── requirements.txt
└── README.md
🏗️ Production Considerations

This project was designed with real-world deployment in mind:

Reproducibility: Environment captured via requirements.txt
Scalability: Can be containerized using Docker
Monitoring: Model performance should be tracked over time for drift
Retraining Strategy: Periodic retraining recommended as customer behavior evolves
📈 Why This Matters

Even small improvements in churn prediction can:

Increase customer lifetime value (CLV)
Reduce acquisition costs
Improve targeted marketing efficiency

This bridges the gap between data science experimentation and business impact.

🔮 Future Enhancements
Add feature importance visualization
Integrate with real-time data pipelines
Deploy via containerized infrastructure (Docker/Kubernetes)
Add model monitoring dashboard
👤 Author

Robert Murphy
Solutions Engineering | AI/ML | Hybrid Cloud
