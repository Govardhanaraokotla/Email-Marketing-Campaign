# 📧 Email Marketing Campaign Analysis 📧

## 📌 Overview
This project analyzes an email marketing campaign launched by an e-commerce company to evaluate its effectiveness and provide data-driven strategies to improve future campaigns. The primary goal is to understand user behavior regarding email interactions and use machine learning to optimize **Click Through Rate (CTR)**.

---

## 📂 Dataset Information
Three CSV files were provided for analysis:

1. **`email_table.csv`** 📨  
   Contains details of each email sent including text type, personalization, time, and user country.

2. **`email_opened_table.csv`** 📬  
   Records emails that were opened by users.

3. **`link_clicked_table.csv`** 🔗  
   Lists emails where users clicked on the link within the email.

---

## 🎯 Objectives

- 📊 Calculate **Open Rate** and **Click Through Rate (CTR)**  
- 🤖 Build a **model** to optimize email targeting  
- 🔍 Discover **patterns in user engagement**  
- 🚀 Simulate potential improvement in performance using machine learning

---

## 📈 Key Metrics

| Metric         | Value     |
|----------------|-----------|
| Open Rate      | 48.8%     |
| Click Through Rate (CTR) | 9.6%       |

---

## 🔍 Exploratory Analysis & Insights

### 📄 Email Text Type
- **Shorter emails** perform better in terms of CTR.

### 👤 Personalization
- Personalized emails significantly improve both open rate and CTR.

### 📆 Weekday Performance
- **Tuesday and Thursday** had the highest engagement.

### ⏰ Hour of the Day
- Best times to send emails: **9 AM – 1 PM** and **5 PM – 7 PM**

### 🌎 User Country
- Some countries showed consistently higher engagement levels, making geo-targeting a viable strategy.

---

## 🤖 Machine Learning Model

We built a **Random Forest Classifier** using the following steps:

### 🏗️ Features Used:
- `email_text` 📝 – Short or long
- `email_version` ✉️ – Personalised or generic
- `hour` 🕐 – Time email was sent
- `weekday` 📆 – Day of the week
- `user_country` 🌍 – User's country
- `user_past_purchases` 🛍️ – Number of past purchases

### 🔧 Preprocessing:
- Categorical features one-hot encoded
- Numerical features passed through directly

### 🔬 Model Training:
- Split: 80% training / 20% testing
- Model: `RandomForestClassifier` from scikit-learn

## 📊 Results

| Metric | Value |
|--------|-------|
| 🎯 Accuracy | `High` |
| 🧪 ROC AUC Score | `~0.84` |
| 📋 Classification Report | Includes precision, recall, F1-score |

✅ **Model can help increase CTR by ~35%** when emails are targeted using predictions.

---

## 📌 Recommendations

✅ Use **short and concise** email content  
✅ **Personalize** emails using the user’s name  
✅ Target users during **mid-week (Tues/Thurs)** and **optimal hours**  
✅ Use **geo-based and behavior-based segmentation**  
✅ Implement **ML model** to optimize future campaigns

---

## 🛠️ Tech Stack

- 📊 **Pandas**, **NumPy** – Data analysis  
- 📉 **Matplotlib**, **Seaborn** – Data visualization  
- 🤖 **Scikit-Learn** – Machine learning  
- 📝 **Jupyter Notebook** / **Google Colab**

---

## 📚 Conclusion

This project demonstrates how data science can be effectively used to optimize marketing campaigns, increase customer engagement, and improve ROI. 📈

---

## ✨ Future Enhancements

- 📬 A/B testing on subject lines and CTA content  
- ⏰ Time zone-based email scheduling  
- 📱 Multi-channel campaign integration (e.g., SMS, push notifications)  

---

## 👨‍💻 Author

**Govardhanarao Kotla**  
🔗 [GitHub](https://github.com/Govardhanaraokotla) | 📫 govardhanaraokotla27@gmail.com

---

