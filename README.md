# 🎫 Customer Support Ticket Analyzer

A Python-based Ticket Analysis System that stores, cleans, analyzes, and extracts insights from customer support tickets. Built for Data Analytics (DA) Module-End Assignment 4.

## 📌 Problem Statement
Customer support teams handle numerous service tickets daily. Analysing support tickets helps identify common issues, customer sentiment, support quality, and areas for improvement.

This project builds a complete analysis system with text cleaning, keyword insights, and priority analytics.

## ✨ Features

- **Step 1: Data Loading** - Preloaded 10 tickets in Dictionary of Lists format
- **Step 2: Dynamic Ticket Addition** - Auto-increment Ticket_No with priority validation (High/Medium/Low)
- **Step 3: Text Cleaning Pipeline**
    - Remove punctuation `.,!?-`
    - Convert multiple spaces → single space
    - Lowercase conversion
    - Leading/trailing space removal
    - Slang replacement (`ok` → `okay`)
- **Step 4: Keyword Insights** - `count_tickets_with_word()` function for case-insensitive search
- **Step 5: Analytics Dashboard**
    - Priority distribution
    - Longest issue description finder
    - Unique words extraction

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** `string`, `pandas` (for display)
- **Concepts Used:** Dictionaries, Lists, String Manipulation, Functions, Loops, Sets, Sorting

## 📂 Project Structure

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `Customer_Support_Ticket_Analyzer.ipynb`
3. Run all cells → Enter new tickets when prompted

### Option 2: Local Jupyter
```bash
git clone https://github.com/yourusername/Customer-Support-Ticket-Analyzer.git
cd Customer-Support-Ticket-Analyzer
pip install pandas
jupyter notebook Customer_Support_Ticket_Analyzer.ipynb

### Option 3: Python Script
bash
python ticket_analyzer.py

📊 Sample Outputjavascript========== STEP 4: Keyword Insights ==========
Tickets containing 'poor': 2
Tickets containing 'good': 3
Tickets containing 'slow': 2
Tickets containing 'excellent': 1

========== STEP 5: Final Summary ==========
2. Priority Analysis:
High Priority: 4
Medium Priority: 3
Low Priority: 3

3. Ticket With Longest Issue Description:
Ticket No: 2
Customer Name: Meera
Cleaned Issue: slow response very poor service
Word Count: 5

📈 Key Insights from Analysis
Sentiment: good (3) > poor (2) → Overall service is satisfactory
Pain Point: slow appears in 20% tickets → Need to improve response time
Priority: High priority tickets are 40% → Requires immediate attention
Unique Words: 22+ unique words identified, useful for auto-tagging future tickets

📝 Deliverables Checklist
Google Colab Notebook with View Access
One-page summary with findings
Cleaned and structured output
GitHub Repository with README[x]
