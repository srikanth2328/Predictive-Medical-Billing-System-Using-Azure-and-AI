# Predictive-Medical-Billing-System-Using-Azure-and-AI

This project uses Artificial Intelligence (AI), Natural Language Processing (NLP), and Machine Learning (ML) to automate and optimize the medical billing and claims approval process. Built using Python, Azure Machine Learning, and Power BI, this system identifies patterns in healthcare claims, predicts approvals, and flags potentially fraudulent claims for auditing.

---

## Project Overview

**Objective:**  
To build a scalable, AI-powered medical billing analysis system that can:
- Classify and analyze claims data
- Predict claim approval status
- Detect anomalies and fraud
- Provide dashboards for real-time insights

---

## My Tools & Used Technologies

- **Python**: Data processing, modeling
- **Pandas / NumPy / Scikit-learn / XGBoost / IsolationForest**
- **NLP**: SpaCy, BERT (for analyzing claim notes)
- **Azure**: Machine Learning Studio, Blob Storage, Form Recognizer
- **Power BI / Streamlit**: Dashboard and visualization
- **SQL**: Data exploration and preprocessing

---

##  Dataset Sources

1. [CMS Medicare Claims Data](https://data.cms.gov/provider-summary-by-type-of-service)

---

##  Workflow

1. **Data Ingestion**: Claims data collected from public datasets or synthetically generated
2. **Preprocessing**: Cleaning, encoding, normalization, and NLP on notes
3. **Modeling**:
   - Approval Prediction Model (Logistic Regression, XGBoost)
   - Fraud Detection Model (Isolation Forest, Autoencoder)
4. **Deployment**: Models deployed using Azure ML as REST APIs
5. **Visualization**: Dashboards built in Power BI for actionable insights

---

## Sample Use Cases

- Hospitals auditing claims for risk and fraud
- Insurance companies prioritizing claims processing
- Revenue cycle teams identifying high-risk claims proactively

---

## Further work  Integrations

- Integrate OCR with Azure Form Recognizer for scanned forms
- Add real-time streaming with Azure Stream Analytics
- Expand to ICD-10/CPT hierarchy analysis and explainable AI

---

## Contact

Built with 💙 by [Srikaanth Pavuluri]  
Feel free to contribute or open an issue!

---
## Credits

Datasets or data used for this project is owened by its respectrive owners. Thanks for your understanding
