# 🛡️ Credit Card Fraud Detection using Deep Learning (ANN)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📝 وصف المشروع | Project Overview
**بالعربية:** نظام ذكاء اصطناعي متطور يعتمد على الشبكات العصبية الاصطناعية (ANN) لكشف محاولات الاحتيال في معاملات البطاقات الائتمانية. يواجه المشروع تحدي "بيانات غير متوازنة" (Imbalanced Data) بنجاح فائق ويقدم نتائج دقيقة جداً لحماية الأنظمة المالية.

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
