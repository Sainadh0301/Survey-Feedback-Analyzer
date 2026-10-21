# Survey Feedback Analyzer

## 📌 Project Overview

The **Survey Feedback Analyzer** is a Python-based project designed to analyze textual customer feedback and extract meaningful insights. It uses Python fundamentals to clean feedback data, count specific words, calculate average ratings, identify the longest comments, and find unique words across survey responses.

## 🎯 Project Objectives

* Store survey feedback using a dictionary of lists.
* Collect additional feedback dynamically from users.
* Clean text by removing punctuation, extra spaces, and uppercase letters.
* Count occurrences of specific words in feedback entries.
* Calculate the average customer rating.
* Identify the feedback with the longest comment.
* Extract unique words from all feedback entries.
* Sort feedback by rating from highest to lowest.

## 🛠️ Tools & Technologies

* **Programming Language:** Python
* **Concepts:** Variables, Lists, Dictionaries, Loops, Conditional Statements, Functions, String Manipulation
* **Functions & Methods:** `input()`, `print()`, `lower()`, `replace()`, `split()`, `join()`, `append()`, `set()`, `zip()`, `sorted()`
* **Libraries:** `re` (optional, for regular-expression-based text cleaning)

## 📊 Key Features

### 1. Feedback Data Management

Stores serial numbers, customer names, written feedback, and ratings in a dictionary of lists.

### 2. Add New Feedback

Accepts additional customer feedback and ratings between 1 and 5, automatically generating serial numbers.

### 3. Text Cleaning

Removes specified punctuation, eliminates extra spaces, trims leading and trailing spaces, and converts text to lowercase.

### 4. Word Frequency Analysis

Counts the number of feedback entries containing specific words, such as `good`, `poor`, and `excellent`.

### 5. Rating Analysis

Calculates the average rating across all feedback records.

### 6. Longest Feedback Identification

Finds the comment containing the highest number of words.

### 7. Unique Word Extraction

Identifies unique words used across all feedback entries without duplicates.

### 8. Feedback Sorting

Sorts feedback entries by rating in descending order using `zip()` and `sorted()`.

## 📁 Project Structure

```text
Survey-Feedback-Analyzer/
│
├── survey_feedback_analyzer.ipynb
└── README.md
```

## 💡 Expected Outcomes

* Clean and standardized customer feedback.
* Word-based insights into customer opinions.
* Average customer satisfaction rating.
* Identification of the longest feedback comment.
* A list of unique words.
* Feedback ranked by customer rating.

## 📈 Business Value

This project demonstrates how basic Python programming can support customer feedback analysis. The results can help businesses identify positive experiences, recognize recurring complaints, and understand customer satisfaction.

## 📚 Learning Outcomes

* Practical use of Python data structures.
* Application of loops and conditional statements.
* Text cleaning and string manipulation.
* Development of reusable functions.
* Basic data analysis and reporting.
* Organizing a Python project for GitHub.

## 👨‍💻 Author

**Sai Nadh**

Aspiring Data Analyst | Python Fundamentals | Data Analytics

## 🏷️ Tags

`Python` `Data Analytics` `Text Analysis` `String Manipulation` `Data Cleaning` `Python Fundamentals` `Customer Feedback`
