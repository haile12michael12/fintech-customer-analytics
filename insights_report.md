# 📊 Bank App Review Analysis – Insights & Recommendations

**Author:** Hailemichael Assefa  
**Challenge:** Fintech App Review Analytics  
**Week:** 2  
**Task:** 4 – Insights and Recommendations  
**Tools:** Python, Seaborn, Matplotlib, WordCloud, Pandas  

---

## 1. Executive Summary

This report analyzes user feedback from the Google Play Store for three Ethiopian banking apps: CBE, BOA, and Dashen.  
We collected and preprocessed 1,200+ reviews and performed sentiment and thematic analysis using NLP tools like VADER, TF-IDF, and spaCy. This report summarizes key drivers, pain points, and recommendations supported by visualizations.

---

## 2. Key Insights

### ✨ Positive Drivers

| Bank | Theme                | Evidence                                |
|------|----------------------|------------------------------------------|
| CBE  | Smooth UI/UX         | 78% of "UI" mentions are positive        |
| BOA  | Fast transfers       | 67% of "transaction" themes are positive |
| Dashen | Biometric login    | High sentiment on login convenience      |

### 🚨 Pain Points

| Bank | Theme                 | Evidence                                |
|------|-----------------------|------------------------------------------|
| CBE  | App crashes           | 70%+ mentions marked negative            |
| BOA  | Login issues          | Common theme in low-rated reviews        |
| Dashen | Delayed alerts      | Users report late push notifications     |

---

## 3. Visualizations

### Sentiment Distribution by Bank  
![sentiment_distribution](sentiment_distribution.png)

### Rating Histogram  
![rating_distribution](rating_distribution.png)

### Positive Word Cloud  
![positive_wordcloud](positive_wordcloud.png)

---

## 4. Recommendations

### CBE
- 🛠 **Fix stability issues** – Frequent crash reports.
- 🎨 **Maintain good UX** – Users praise navigation.

### BOA
- 🔐 **Simplify login flow** – Login issues drive 1-star reviews.
- 💬 **Add live chat/helpbot** – Users feel unsupported.

### Dashen
- 📲 **Enable instant push alerts** – Transaction delays noted.
- 👥 **Improve feedback follow-up** – Users feel unheard.

---

## 5. Ethical Considerations

- **Bias risk**: Users are more likely to post negative reviews when frustrated.
- **Sampling**: Data comes only from Android users (Google Play).
- **Volume**: 400 reviews per bank may not fully represent all users.

---

## 6. Next Steps

- Compare with Apple Store reviews.
- Correlate sentiment with app update logs.
- Use BERT-based topic modeling for deeper clustering.

---

