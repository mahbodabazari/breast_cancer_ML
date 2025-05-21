

# Breast Cancer Probability Prediction / پیش‌بینی احتمال سرطان سینه


در این پروژه، با استفاده از دیتاست Breast Cancer Wisconsin (Diagnostic)، هدف ما بررسی مدل‌هایی برای پیش‌بینی **احتمال مثبت بودن** بیماری سرطان سینه است.

با توجه به ماهیت حساس این مسئله که با سلامت و نگرانی بیماران در ارتباط است، عملکرد مدل باید به‌گونه‌ای باشد که موارد **مثبت را تا حد ممکن به درستی تشخیص دهد**. به عبارتی دیگر:

- تشخیص اشتباه یک بیمار **مثبت** به عنوان **منفی** (False Negative) خسارت بیشتری دارد.
- در مقابل، اگر یک بیمار **منفی** به اشتباه **مثبت** تشخیص داده شود (False Positive)، خطر کمتری دارد و می‌توان با آزمایش‌های تکمیلی رفع ابهام کرد.

بنابراین، تمرکز اصلی بر روی معیارهایی مانند:
- **ROC AUC Score**
- **Recall کلاس مثبت**
- **تحلیل احتمال پیش‌بینی‌ها (probability outputs)**

می‌باشد تا بتوانیم مدلی توسعه دهیم که به درستی بیماران نیازمند توجه پزشکی را شناسایی کند.

---


This project utilizes the **Breast Cancer Wisconsin (Diagnostic)** dataset to develop models that predict the **probability of a positive diagnosis** for breast cancer.

Because of the sensitive nature of this medical problem and its psychological impact on patients, model evaluation is focused on the **correct identification of positive cases**.

Key considerations:
- A **false negative** (predicting a positive case as negative) can be **dangerous** and lead to undetected illness.
- A **false positive** is less critical and can be clarified through additional tests.

Hence, we prioritize metrics such as:
- **ROC AUC Score**
- **Recall for the positive class**
- **Analysis of probabilistic predictions**

The ultimate goal is to ensure the model can correctly identify high-risk individuals and support early detection.

---

## 📁 Dataset

- Breast Cancer Wisconsin (Diagnostic): Available in scikit-learn datasets (`load_breast_cancer`) or from [UCI Repository](https://archive.ics.uci.edu/ml/datasets/breast+Cancer+Wisconsin+(Diagnostic))

---

## ⚙️ Tools and Technologies

- Python
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Logistic Regression, Random Forest, PCA
- ROC AUC, Confusion Matrix, Classification Report

---

## ✅ Goal

Maximize the detection of **true positive** cancer cases while minimizing **false negatives**, to support reliable early diagnosis.

