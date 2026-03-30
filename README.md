# 📊 InsightED: Academic Data Analytics System

## Project Overview
InsightED is a decision-support data analytics system designed for universities. Its primary objective is to process raw student feedback data, extract meaningful insights using data analysis and NLP, and present highly actionable conclusions to help university administrators and faculty improve academic performance and student satisfaction.

## Core Features
* **Insight-First Dashboard**: Highlights critical issues rather than just displaying raw data.
* **KPI Tracking**: Monitors Average Satisfaction Score, Negative Feedback percentage, Course Difficulty, and Faculty Ratings.
* **Sentiment Analysis**: Processes text-based feedback to classify student comments as Positive, Neutral, or Negative.
* **Automated Insights Panel**: Generates critical text insights automatically (e.g., "Data Structures has 40% negative feedback").

## Tech Stack
* **Frontend**: Streamlit
* **Data Processing**: Python, Pandas, NumPy
* **NLP & Data Science**: NLTK, TextBlob, Scikit-learn
* **Visualizations**: Matplotlib, Plotly

---

## 📚 Learning Milestone Submission: Understanding the Data Science Lifecycle

### 1. Explaining the Lifecycle (Question -> Data -> Insight)
* **The Question**: The data science lifecycle must always begin with a carefully targeted question. Jumping directly into a dataset without a clear goal leads to aimless exploration. Formulating a specific question acts as a compass—it defines the scope, restricts us to relevant data, and gives the project a concrete definition of success.
* **Data as Evidence**: Data is the objective evidence we need to answer our question. Before writing complex algorithms, we have to understand where the data came from, its biases, and its format. We have to ensure that the data actually represents the real-world academic environment we are trying to analyze.
* **Generating Insight**: Insights are not simply charts or raw numbers; they are the conclusions we draw when we interpret the data *through the lens of our core question*. True insight shifts the focus from "What happened?" to "Why did it happen, and what decision should we make to fix it?"

### 2. Applying the Lifecycle to InsightED
* **The Question:** "Which specific courses are causing the highest rate of negative student feedback, and what specific topics or teaching styles are driving this dissatisfaction?"
* **The Type of Data Needed:** We need end-of-semester student survey feedback. This comes directly from the university's evaluation systems. It represents quantitative metrics (ratings from 1-5 on faculty and course difficulty) and qualitative metrics (open-ended text comments from students).
* **The Useful Insight:** Simply stating "Data Structures has a 2.5 rating" is just a fact, not an insight. An actionable insight would be: *"Data Structures has a 40% negative feedback rate specifically because students are frequently using the phrases 'fast teaching' and 'too theoretical' in their reviews, indicating the curriculum pace must be adjusted immediately."*

---

## 🛠️ Environment Setup: Python & Anaconda

### 1. System Specifications
* **Operating System:** Windows
* **Python Version:** 3.13.0
* **Anaconda Version:** [Pending Installation]

### 2. Installation Steps Followed
1. **Python:** Verified the existing global Python installation via terminal.
2. **Anaconda:** Downloaded the Anaconda installer for Windows and completed the setup wizard.
3. **Verification:** Validated that both Python and Conda commands are globally accessible and return the correct version numbers.

### 3. Verification Commands & Outputs
```bash
> python --version
Python 3.13.0

> conda --version
# (Please run this in your terminal after installing Anaconda and paste the output here)
conda 24.x.x 
```

---

## 📓 Jupyter Notebook Workspace Setup

### 1. Workspace Organization
To ensure the project remains organized and free from clutter, we utilize a dedicated folder structure for running our Jupyter notebooks:
* **Root Directory**: `sprint-3/` (This must be the directory from which Jupyter is launched to maintain correct relative paths).
* **Notebooks Directory**: `sprint-3/notebooks/` (All notebooks should be saved inside this explicit folder).

### 2. Verification Steps Followed
1. Launched Jupyter from the project root using `jupyter notebook`.
2. Verified the Jupyter Home interface displays the correct project folders.
3. Successfully created and executed a Python print cell within the newly established `notebooks/01_jupyter_setup.ipynb` testing notebook.
