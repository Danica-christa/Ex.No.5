# EXPERIMENT 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

### Date: 02-09-2026

### Name: DANICA CHRISTA

### Register no. 212223240022

## PROJECT TITLE

**AI-Based Student Expense Tracker**

---

## AIM

To compare different prompting techniques and evaluate their effectiveness in solving a real-world engineering problem using an AI-based student expense tracking scenario.

---

# AI TOOLS REQUIRED

- ChatGPT

---

# EXPERIMENT OVERVIEW

**AI-Based Student Expense Tracker** is an AI-based application designed to help students record, categorize and analyse their daily expenses. The system aims to identify spending patterns and provide useful recommendations for better financial management.

Students often find it difficult to manually track their expenses and understand where their money is being spent. Manual expense tracking can be time-consuming and may not provide useful insights into spending behaviour.

The proposed system uses Artificial Intelligence and Machine Learning to automatically categorize expenses into categories such as **Food, Travel, Education, Shopping and Entertainment** and provide spending recommendations.

For this experiment, the selected engineering problem is:

> **How can an AI-based student expense tracker automatically categorize expenses, analyse spending patterns and provide practical recommendations to students?**

The same expense-management problem was given to ChatGPT using four different prompting techniques. The generated responses were then compared based on **relevance, accuracy, completeness, clarity, feasibility and usefulness**.

---

# SELECTED ENGINEERING SCENARIO

The following student expense scenario is considered for the experiment.

```text
Expense Description: "Lunch at college canteen"
Amount: ₹120

Expected Category:

Food

Another example is:

Expense Description: "Monthly bus pass"
Amount: ₹800

Expected Category:

Travel
## Problem in the System

The main engineering problem is to automatically identify the category of an expense based on information such as the expense description and amount.

For example:

| Expense Description | Amount | Expected Category |
| ------------------------------------------ | ------ | ------------- |
| Lunch at college canteen | ₹120 | Food |
| Monthly bus pass | ₹800 | Travel |
| Online Python course | ₹500 | Education |
| Bought headphones | ₹1,500 | Shopping |
| Movie ticket | ₹250 | Entertainment |

The AI-based system should:

- Identify the expense category.
- Analyse spending patterns.
- Calculate category-wise expenditure.
- Identify excessive spending.
- Provide useful recommendations.
- Help students manage their budgets.

# PROMPTING TECHNIQUE 1 – STRAIGHTFORWARD PROMPT

## Prompt

Suggest a machine learning approach for automatically categorizing student expenses and providing spending recommendations in an AI-based student expense tracker.

## AI-GENERATED OUTPUT

The AI suggested collecting historical student expense data and categorizing transactions into categories such as Food, Travel, Education, Shopping and Entertainment.

A supervised machine learning algorithm such as Logistic Regression, Decision Tree or Random Forest can be trained using labelled expense data.

The model can use information such as:

- Expense description
- Expense amount
- Date
- Transaction type

For text-based expense descriptions, techniques such as TF-IDF can be used to convert text into numerical features.

After categorizing expenses, the system can calculate monthly spending and provide recommendations based on spending patterns.

## Suggested Solution

~~~text
Expense Input
      ↓
Data Preprocessing
      ↓
Feature Extraction
      ↓
Machine Learning Model
      ↓
Expense Category
      ↓
Spending Analysis
      ↓
Recommendation
~~~

## Observation

The straightforward prompt successfully provided a general machine learning solution. However, it did not request detailed information about dataset preparation, model evaluation, implementation or system architecture.

# PROMPTING TECHNIQUE 2 – ROLE-BASED PROMPTING

## Prompt

Act as a senior machine learning engineer designing a practical AI-based student expense tracker. Analyze how student expenses can be automatically categorized and how spending recommendations can be generated. Explain the dataset, preprocessing, machine learning algorithm, evaluation metrics and implementation steps. Keep the solution suitable for a final-year AIML engineering project.

## AI-GENERATED OUTPUT

### Data Collection

The system should collect historical expense records containing:

- Expense description
- Amount
- Date
- Category
- Payment method

Example:

| Description | Amount | Category |
| ------------------------- | ------ | --------- |
| College lunch | ₹120 | Food |
| Bus ticket | ₹30 | Travel |
| Online course | ₹500 | Education |
| New headphones | ₹1,500 | Shopping |

### Data Preprocessing

The collected data should be cleaned before training the model.

The preprocessing steps include:

- Removing duplicate records.
- Handling missing values.
- Converting text to lowercase.
- Removing unnecessary symbols.
- Converting text into numerical features.

### Machine Learning Algorithm

The following algorithms can be considered:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest

Logistic Regression can be used as a baseline model, while Random Forest can be tested for improved classification performance.

### Model Evaluation

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Recommendation System

After categorizing expenses, the system can calculate monthly spending for each category.

For example:

~~~text
Food        → ₹4,500
Travel      → ₹2,000
Shopping    → ₹5,000
Education   → ₹1,500
~~~

If spending in a category exceeds the student's budget, the system can provide a recommendation to reduce unnecessary expenditure.

## Observation

Role-based prompting produced a more professional and domain-specific response. It considered the dataset, preprocessing, machine learning algorithms, evaluation and recommendation system.

# PROMPTING TECHNIQUE 3 – CONSTRAINT-BASED PROMPTING

## Prompt

Design a solution for an AI-based student expense tracker.

Follow these constraints:

- Identify the data required for the system.
- Explain how the data should be preprocessed.
- Identify suitable machine learning algorithms.
- Explain why an algorithm should be selected.
- Explain how expenses can be automatically categorized.
- Explain how spending recommendations can be generated.
- Mention suitable evaluation metrics.
- Keep the solution simple and practical.
- Do not require expensive hardware or services.
- Make the solution suitable for a final-year AIML project.
- Present the solution using the format: Requirement → Explanation → Recommendation → Implementation.

Problem:

Develop an AI-based system that automatically categorizes student expenses into Food, Travel, Education, Shopping and Entertainment and provides spending recommendations.

## AI-GENERATED OUTPUT

### Requirement 1: Expense Data

**Explanation:** The system requires historical student expense records.

**Recommendation:** Collect expense descriptions, amounts, dates and categories.

**Implementation:**

| Description | Amount | Category |
| ------------------------- | --- | --------- |
| Lunch | 120 | Food |
| Bus Pass | 800 | Travel |
| Python Course | 500 | Education |

### Requirement 2: Data Preprocessing

**Explanation:** Raw expense descriptions may contain unnecessary characters and inconsistent formats.

**Recommendation:** Clean and normalize the data before training.

**Implementation:**

- Remove missing values.
- Remove duplicate records.
- Convert text to lowercase.
- Remove unnecessary symbols.
- Convert text into numerical features.

### Requirement 3: Feature Extraction

**Explanation:** Machine learning algorithms require numerical input.

**Recommendation:** Use TF-IDF for text-based expense descriptions.

**Implementation:**

~~~text
Expense Description
        ↓
Text Cleaning
        ↓
TF-IDF
        ↓
Numerical Features
~~~

### Requirement 4: Machine Learning Model

**Explanation:** The model should predict the category of a new expense.

**Recommendation:** Use Logistic Regression as a simple baseline and compare it with Random Forest or Naive Bayes.

### Requirement 5: Spending Recommendation

**Explanation:** The system should identify unusual or excessive spending.

**Recommendation:** Compare category-wise expenditure against a predefined budget.

Example:

~~~text
Shopping Budget = ₹3,000
Actual Spending = ₹5,000
~~~

The system can generate:

**Recommendation:**

Your shopping expenditure is above the planned budget.

Consider reducing unnecessary shopping expenses.

### Requirement 6: Evaluation

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Observation

The constraint-based prompt produced a highly structured and practical response. It covered the dataset, preprocessing, feature extraction, model selection, recommendations and evaluation while following the specified requirements.

# PROMPTING TECHNIQUE 4 – STEP-BY-STEP PROMPTING

## Prompt

Perform a systematic analysis of the following engineering problem for the AI-Based Student Expense Tracker.

Step 1: Understand the purpose of the expense tracker.

Step 2: Identify the data required for automatically categorizing expenses.

Step 3: Explain how the data should be cleaned and preprocessed.

Step 4: Identify suitable machine learning algorithms.

Step 5: Select the most suitable algorithm and explain why.

Step 6: Explain how the model should be trained and tested.

Step 7: Explain how spending patterns can be analysed.

Step 8: Explain how personalized recommendations can be generated.

Step 9: Provide the complete system architecture.

Step 10: Mention possible challenges and solutions.

Provide a practical solution suitable for a final-year AIML project.

## AI-GENERATED OUTPUT

### Step 1 – Understand the Problem

The system is designed to help students monitor their daily expenses and understand their spending behaviour.

The main functions are:

- Expense recording
- Automatic categorization
- Spending analysis
- Budget monitoring
- Recommendation generation

### Step 2 – Identify Required Data

The dataset should contain:

- Expense Description
- Amount
- Date
- Category
- Payment Method

Example:

| Expense | Amount | Category |
| --------------------- | ------ | --------- |
| College lunch | ₹120 | Food |
| Bus ticket | ₹30 | Travel |
| Programming course | ₹500 | Education |
| Shoes | ₹1,500 | Shopping |

### Step 3 – Data Preprocessing

The data should be cleaned by:

- Removing duplicate records.
- Handling missing values.
- Converting text to lowercase.
- Removing unnecessary characters.
- Converting text into numerical features.

### Step 4 – Algorithm Selection

Possible algorithms include:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest

### Step 5 – Recommended Algorithm

Logistic Regression can be used as a baseline because it is simple, fast and suitable for text classification.

Random Forest can also be tested and compared with the baseline model.

### Step 6 – Training and Testing

The dataset can be divided into:

~~~text
80% → Training Data
20% → Testing Data
~~~

The model is trained using the training dataset and evaluated using unseen testing data.

### Step 7 – Spending Analysis

The system can calculate category-wise monthly expenses.

Example:

~~~text
Food          → ₹4,500
Travel        → ₹2,000
Education     → ₹1,500
Shopping      → ₹5,000
Entertainment → ₹1,000
~~~

This information can be displayed using charts or a dashboard.

### Step 8 – Recommendation Generation

The recommendation engine can compare actual spending with predefined budgets.

For example:

~~~text
Category: Shopping
Budget: ₹3,000
Actual Spending: ₹5,000
~~~

The system can generate:

Your shopping expenses are higher than your planned budget.

Try reducing unnecessary purchases this month.

### Step 9 – System Architecture

~~~text
Student
   ↓
Expense Entry
   ↓
Data Preprocessing
   ↓
Feature Extraction
   ↓
ML Classification Model
   ↓
Expense Category
   ↓
Spending Analysis
   ↓
Recommendation Engine
   ↓
Student Dashboard
~~~

### Step 10 – Challenges and Solutions

| Challenge | Solution |
|---|---|
| Insufficient training data | Collect more labelled expense records |
| Incorrect categories | Improve data labelling |
| New/unrecognized expenses | Retrain the model with new examples |
| Missing values | Apply suitable data preprocessing |
| Low prediction accuracy | Compare multiple ML algorithms |

## Observation

Step-by-step prompting produced a systematic and comprehensive solution. It guided the AI through the complete problem-solving process from data collection to recommendation generation and system implementation.

# COMPARISON OF PROMPTING TECHNIQUES

| Prompting Technique | Relevance | Accuracy | Completeness | Clarity | Feasibility | Usefulness |
|---|---|---|---|---|---|---|
| Straightforward Prompt | Good | Very Good | Medium | Good | Very Good | Good |
| Role-Based Prompt | Very Good | Very Good | Good | Very Good | Very Good | Very Good |
| Constraint-Based Prompt | Excellent | Excellent | Excellent | Excellent | Excellent | Excellent |
| Step-by-Step Prompt | Excellent | Excellent | Excellent | Excellent | Excellent | Excellent |

# Overall Finding

The experiment demonstrates that prompt specificity and structure have a significant impact on AI-generated solutions.

The straightforward prompt produced a general machine learning approach. Role-based prompting provided more domain-specific information. Constraint-based prompting produced a structured and practical solution, while step-by-step prompting provided the most systematic explanation.

For simple questions, a straightforward prompt may be sufficient. However, for an engineering project such as an AI-Based Student Expense Tracker, structured prompts provide more detailed, consistent and actionable solutions.

# RESULT

The experiment was successfully executed using ChatGPT for the AI-Based Student Expense Tracker project.
