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

---

## 📊 Critical Evaluation

### ✅ Accuracy and Relevance of the AI-Generated Output
NotebookLM’s responses were factually accurate and directly sourced from the uploaded document. It correctly identified:
- The proposed technique (Ratio-Based Data Balancing)
- The top-performing model (XGBoost)
- Dataset origin and features

Answers matched the document's intent and content, showing a good level of understanding with no hallucinated information.

### 🎓 Usefulness in Academic Workflows
Very useful for:
- Verifying understanding of core concepts
- Preparing for group discussions or presentations
- Efficiently retrieving document-specific answers for assignments

This feature mimics the benefits of Ctrl+F + comprehension.

### ⚠ Limitations and Concerns
- May miss subtleties in documents that contain abstract or complex language
- Performs better with direct, simple questions than with open-ended or multi-layered ones
- Tends to be factual rather than analytical — additional reflection is needed for academic writing

---

## ✅ Summary
The Q&A feature in NotebookLM was an efficient way to extract focused insights from the document. It’s especially helpful in academic contexts like assignment prep or study note creation. However, students should still apply their own analysis and critical thinking when using the tool for higher-level academic tasks.

