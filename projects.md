# Projects

Selected machine learning projects focused on security, NLP, and applied modeling, emphasizing practical evaluation, feature engineering, and deployable systems.

---

## Android Malware Detection
![Android Malware Detection](asstes/android_malware.png)

**Domain:** Security · Deep Learning  

Built an Android malware detection pipeline using deep learning models with optimized feature representations and ensemble methods. Evaluated the system under realistic class imbalance to reduce overfitting and improve generalization beyond benchmark settings.

**Tech stack:** CNN, ensemble learning  
**Evaluation:** Precision, recall, F1-score under imbalanced data  
**Outcome:** IEEE conference publication  

**Key engineering takeaway:**  
Designing for class imbalance early has a larger impact on real-world performance than model complexity alone.

🔗 GitHub: https://github.com/mehedi-shakil/Android-Malware-Detection

---

## Optimized IoT Security (Hybrid Attention IDS)
![Optimized IoT Security](asstes/optimized_iot.png)

**Domain:** IoT Security · Intrusion Detection  

Designed an intrusion detection framework for IoT traffic using a hybrid attention-based model to capture informative patterns across heterogeneous and highly imbalanced network data. Focused on stable multi-class detection rather than single-metric optimization.

**Tech stack:** Deep learning, attention mechanisms  

**Key engineering takeaway:**  
Attention mechanisms help stabilize detection in heterogeneous traffic, but only when paired with careful data handling.

🔗 GitHub: https://github.com/mehedi-shakil

---

## Hate Speech Detection (NLP)
![Hate Speech Detection](asstes/hate_speech.png)

**Domain:** NLP · Transformers  

Fine-tuned a transformer-based model for hate speech classification with structured preprocessing and hyperparameter tuning. Deployed the trained model as a REST API to support real-time inference and downstream integration.

**Tech stack:** BERT, Hugging Face Transformers  
**Deployment:** Flask API  

**Key engineering takeaway:**  
Model performance alone is insufficient without a deployment interface that supports fast and reliable inference.

🔗 GitHub: https://github.com/mehedi-shakil/hate-speech-api

---

## Fake Instagram Account Detection
![Fake Instagram Detection](asstes/fake_instagram.png)

**Domain:** Social Media Security · Machine Learning  

Developed a supervised learning pipeline to detect fake Instagram accounts using profile-level and behavioral features. Emphasized feature selection and robustness to noisy, partially informative social data.

**Tech stack:** Feature engineering, supervised ML  

**Key engineering takeaway:**  
Careful feature selection often outperforms complex models when labels and signals are noisy.

🔗 GitHub: https://github.com/mehedi-shakil

---

## Time Series Forecasting (Tesla Stock)
![Tesla Forecasting](asstes/tesla_forecast.png)

**Domain:** Time Series Analysis · Forecasting  

Implemented and compared classical time-series models and deep learning approaches to forecast Tesla stock closing prices. Focused on understanding model behavior, trend sensitivity, and limitations rather than short-term accuracy.

**Tech stack:** ARIMA, LSTM  

**Key engineering takeaway:**  
Model interpretability and stability matter more than marginal accuracy gains in volatile time-series data.

🔗 GitHub: https://github.com/mehedi-shakil/Time_Series_Forecasting___TSLA_Close
