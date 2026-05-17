# 📊 Stock Price vs Revenue Analysis (Tesla & GameStop)

This project explores the relationship between stock price movements and company fundamentals by analyzing Tesla and GameStop. The goal is to understand whether stock prices truly reflect financial performance or if other factors play a significant role.

---

## 🚀 Project Overview

In this analysis, I worked with two types of data:

- **Stock price data** (daily) using `yfinance`
- **Revenue data** (annual) extracted from a public financial source

By combining both, I was able to compare how market behavior aligns (or doesn’t) with actual company performance.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- Matplotlib  
- yfinance  
- Web scraping (BeautifulSoup / pandas.read_html)

---

## 📈 Key Visualizations

The project includes:

- Tesla stock price over time  
- Tesla revenue over time  
- GameStop stock price over time  
- GameStop revenue over time  
- Combined comparison: Tesla stock price vs revenue (dual-axis chart)

---

## 🔍 Key Insights

- Tesla shows strong revenue growth, but its stock price increased much faster and with higher volatility, especially after 2020. This suggests that market expectations and sentiment played a major role.

- The stock price often moved ahead of revenue growth, indicating that investors tend to anticipate future performance rather than react only to current results.

- GameStop presents a clear disconnect between fundamentals and price, with declining revenue but a sharp spike in stock price around 2021.

- Overall, stock prices do not always reflect financial performance in the short term, as they are influenced by speculation, investor behavior, and external market dynamics.

---

## ⚠️ Limitations

- Stock price data is daily, while revenue data is annual, which makes direct comparison less precise  
- The analysis does not include other financial metrics (profit, margins, etc.)  
- External factors influencing stock prices are not explicitly modeled  

---

## 💡 What I Learned

This project helped me understand how to:

- Extract and clean real-world financial data  
- Handle inconsistent formats (e.g., "$", "B", text values)  
- Build clear and meaningful visualizations  
- Interpret the gap between market behavior and company fundamentals  

---

## 📌 Future Improvements

- Add profit (net income) analysis  
- Align data frequencies (monthly vs yearly)  
- Include correlation analysis  
- Build an interactive dashboard  

---

## 🙌 Final Thoughts

This project shows that analyzing stock data is not just about numbers — it's also about understanding behavior, expectations, and how markets actually work.

