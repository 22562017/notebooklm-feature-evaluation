# 🤖 Case 2: Document-Based Question Answering

## 🎓 Scenario
I asked specific questions about the uploaded article **“Enhancing Customer Retention in the Telecom Industry with Machine Learning...”** to simulate writing a critical review or preparing for a class discussion.

---

## 🚀 Features Tested

### ✅ Source-Grounded Q&A
NotebookLM provided accurate, document-based answers:
- **Q:** “What technique does the paper propose?”  
  **A:** Ratio-Based Data Balancing  
- **Q:** “Which model gave the highest performance?”  
  **A:** XGBoost with a 75:25 train-test split  
- **Q:** “What dataset was used?”  
  **A:** Kaggle Telecom Customer Dataset with 20 features

### ✅ In-Context Citations
Each response included a “View source” link pointing directly to the relevant section of the article.

---

## 🧠 Reflection
The Q&A feature significantly reduced the time needed to locate key information. It was particularly effective for quickly answering assignment-style questions. However, it was less accurate when handling multi-part or open-ended questions that required deeper reasoning.

