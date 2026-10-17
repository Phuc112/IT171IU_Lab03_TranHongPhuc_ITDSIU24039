# IT171IU – Statistical Learning
## Lab 3: Classification (ISLP Chapter 4)

### Student Information
- **Full Name:** Trần Hồng Phúc
- **Student ID:** ITDSIU24039
- **Class Group:** IT171IU – Lab Group 01
- **University:** International University – VNU-HCM (HCMIU)

---

### Folder Structure
```text
IT171IU_Lab03_FullName_StudentID/
├── IT171IU_Lab03_FullName_StudentID.ipynb   # Completed notebook with all code cells executed
├── IT171IU_Lab03_Report.pdf                 # Filled lab report / handout with answers and plots
├── README.md                                # Submission instructions and details
                         
* **Overview & Objectives**
This repository contains the completed assignment for Lab 3: Classification, covering the following concepts and methods:

Logistic Regression: Model fitting (sm.GLM and LogisticRegression), log-odds interpretation, and decision thresholds.

Generative Models: Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), and Naive Bayes using Bayes' theorem.

K-Nearest Neighbors (KNN): Distance-based classification and the necessity of feature standardization (StandardScaler).

Evaluation Metrics: Confusion matrices, accuracy, sensitivity, specificity, precision, ROC curves, and AUC scores.

Poisson Regression: Modeling non-negative count data on the Bikeshare dataset.

* **How to Run the Notebook**
Option 1: Google Colab (Recommended)
Open Google Colab.

Select File → Upload notebook and upload IT171IU_Lab03_FullName_StudentID.ipynb.

Fill in your information in the first code cell (STUDENT_NAME, STUDENT_ID, CLASS_GROUP).

Run the Setup cell to automatically install missing packages (e.g., ISLP) and fetch required datasets.

Execute all cells in order via Runtime → Run all.

Option 2: Local Environment (Jupyter / VS Code / PyCharm)
Ensure Python 3.8+ is installed.

Install dependencies:

Bash
pip install numpy pandas matplotlib statsmodels scikit-learn ISLP
Open the notebook in your preferred environment and run all cells sequentially from top to bottom.

* **Policy Statement on AI Assistant Usage**
An AI assistant was used during this lab solely as a learning aid in accordance with course guidelines:

Syntax Support: Helping resolve data indexing and formatting patterns in Pandas and Statsmodels.

Code Structuring: Organizing multi-model comparison workflows and visualization code.

Concept Refinement: Ensuring text interpretations were clear and well-structured.

All code outputs, logic checks, and text submissions were reviewed, tested, and verified manually prior to final packaging and submission.