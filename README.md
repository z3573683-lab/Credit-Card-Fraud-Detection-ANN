# 🛡️ Credit Card Fraud Detection using Deep Learning (ANN)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📝 وصف المشروع | Project Overview
**بالعربية:**

نظام ذكاء اصطناعي متطور يعتمد على الشبكات العصبية الاصطناعية (ANN) لكشف محاولات الاحتيال في معاملات البطاقات الائتمانية. يواجه المشروع تحدي "بيانات غير متوازنة" (Imbalanced Data) بنجاح فائق ويقدم نتائج دقيقة جداً لحماية الأنظمة المالية.

**In English:**

An advanced AI system built with Artificial Neural Networks (ANN) to detect fraudulent credit card transactions. The project successfully tackles the "imbalanced data" challenge, providing highly accurate results to secure financial systems.

---

## 🚀 المميزات التقنية | Technical Features
* **Data Balancing:** استخدام تقنية **SMOTE** لموازنة بيانات الاحتيال.
* **Architecture:** شبكة عصبية عميقة (Deep ANN) مع طبقات Dropout لمنع الـ Overfitting.
* **Performance:** * **AUC Score:** 0.98 (قدرة تمييز فائقة).
    * **Recall:** 90% (نجاح كبير في صيد العمليات المشبوهة).
* **Live Inference:** كود مدمج لاختبار عينات عشوائية والتنبؤ بها فورياً.

[attachment_0](attachment)

---

## 📊 النتائج | Results
### 1. Confusion Matrix
الموديل أظهر دقة مذهلة في بيانات الاختبار:
* **True Negatives:** 56,664 (عمليات سليمة تم كشفها).
* **True Positives:** 88 (عمليات احتيال تم ضبطها بنجاح).

### 2. ROC Curve
وصل منحنى ROC إلى مساحة تحت المنحنى (AUC) قدرها **0.98**، مما يضع هذا النموذج في فئة النماذج "المثالية" (Ideal Models).



---
## 📉 Credit Card Fraud Detection Results

### 1. Training History (Accuracy & Loss)
The model performance over training epochs showing the convergence of accuracy and loss functions.

![Accuracy Graph](< <img width="398" height="581" alt="graph_accuracy" src="https://github.com/user-attachments/assets/efad5ff8-ae6f-422e-8483-aa86335b8084" />
  >)

Predictive Maintenance Pipeline Architecture: A two-stage system where Model 1 performs binary fault detection to identify system status, followed by Model 2 for multi-class classification to diagnose the specific failure type. This hierarchical approach ensures maximum diagnostic accuracy.

​بالعربي

​هيكلية نظام الصيانة التنبؤية: نظام يعتمد على مرحلتين؛ حيث يقوم الموديل الأول باكتشاف وجود العطل، ثم يأتي دور الموديل الثاني لتشخيص نوع العطل بدقة. هذا التصميم الهيكلي يضمن أعلى درجات الدقة في التنبؤ والتشخيص الصناعي


![Loss Graph](< <img width="456" height="597" alt="graph_Loss" src="https://github.com/user-attachments/assets/131a737d-e760-4957-a6de-193b1a5fc2ce" />
  >)

### 2. Confusion Matrix & Prediction Samples
Evaluation of the model's ability to distinguish between normal transactions and fraudulent ones.

![Confusion Matrix](<  <img width="842" height="690" alt="Confusion_Matrix" src="https://github.com/user-attachments/assets/fe934cd9-2b17-4331-a8e1-b197c09437da" />
 >)
![Model Predictions](< <img width="576" height="193" alt="photo_Predicted" src="https://github.com/user-attachments/assets/674e3522-9e28-45f3-8b25-f41260466591" />
  >)

### 3. Classification Report
Detailed analysis of precision, recall, and f1-score, which are critical for detecting fraud cases effectively.

![Classification Report](< <img width="595" height="255" alt="Classification_Report" src="https://github.com/user-attachments/assets/7db592e6-ec57-4367-9185-af1f2ab7795d" />
  >)




## 🛠️ كيفية الاستخدام | How to Use
1. قم بتحميل ملف الموديل `credit_card_fraud_model.h5`.
2. قم بتحميل الـ Scaler `data_scaler.joblib`.
3. استخدم الدالة `predict()` لتوقع أي عمليات جديدة.

---

## 📂 هيكل المشروع | Project Structure
* `Notebook.ipynb`: الملف البرمجي بالكامل.
* `credit_card_fraud_model.h5`: الموديل المدرب جاهز للاستخدام.
* `data_scaler.joblib`: أداة معالجة البيانات.

---

## 👤 التواصل | Contact
**Developed by [MOHAMED BELAL]** *Project completed in February 2026*
MY PHONE [01018689118]
