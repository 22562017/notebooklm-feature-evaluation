# 🤖 Case 2: Document-Based Question Answering

## Scenario
I asked questions about the uploaded article to simulate writing a critical review or preparing for a discussion.

## Features Tested

### ✅ Source-Grounded Q&A
- Asked: **“What technique does the paper propose?”**
  - Answer: Ratio-Based Data Balancing
- Asked: **“Which model gave the highest performance?”**
  - Answer: XGBoost at 75:25 ratio
- Asked: **“What dataset was used?”**
  - Answer: Kaggle Telecom Customer Dataset

### ✅ In-Context Citations
- Each answer had a “View source” link to the exact page in the article

## Reflection
The Q&A tool was accurate and saved time searching for details. But it occasionally struggled with multi-part or vague questions.
