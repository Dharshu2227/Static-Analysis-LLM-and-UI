# Integrate Static Analysis, LLM and UI

## 📌 Project Overview

This project demonstrates the integration of **Static Analysis**, **Large Language Models (LLMs)**, and a **User Interface (UI)** to create a simple AI-assisted code review system.

The system combines outputs from static-analysis tools such as Flake8, Pylint, and Bandit, generates an LLM-style review, and displays the results through a Gradio-based user interface.

The objective is to provide developers with a user-friendly way to analyze code, understand detected issues, and receive recommended fixes.

---

## 🎯 Objectives

The main objectives of this project are:

* Integrate static-analysis results into a single review workflow.
* Simulate LLM-based code review.
* Display analysis results through a graphical user interface.
* Classify issues based on severity.
* Provide recommended fixes for detected issues.
* Demonstrate AI-assisted software quality assessment.

---

## 🛠️ Technologies Used

| Technology   | Purpose                               |
| ------------ | ------------------------------------- |
| Python       | Application development               |
| Flake8       | Style and formatting analysis         |
| Pylint       | Code quality analysis                 |
| Bandit       | Security vulnerability analysis       |
| Gradio       | User Interface                        |
| LLM Concepts | Issue explanation and recommendations |
| Google Colab | Execution environment                 |
| GitHub       | Version control and hosting           |

---

## 📂 Project Structure

```text id="jfxq0t"
Integrate-Static-Analysis-LLM-and-UI/
│
├── static_analysis_llm_ui.py
├── README.md
```

---

## 🔍 Static Analysis Reports

The project combines findings from three analysis tools.

### Flake8

```text id="r7cjlwm"
E231 missing whitespace after ','
```

### Pylint

```text id="gjmtyc"
Unused import os
Unused variable 'temp'
```

### Bandit

```text id="i2ahpj"
Possible hardcoded password
```

---

## 🤖 LLM Review

The LLM review explains identified issues and suggests fixes.

### Example Findings

#### Issue: Missing Whitespace After Comma

**Severity:** Low

**Suggested Fix:**

```python id="a7crzv"
def add(a, b):
```

---

#### Issue: Unused Import

**Severity:** Medium

**Suggested Fix:**

Remove the unused import statement.

---

#### Issue: Unused Variable

**Severity:** Medium

**Suggested Fix:**

Remove the variable or use it where required.

---

#### Issue: Hardcoded Password

**Severity:** High

**Suggested Fix:**

Store credentials in environment variables instead of source code.

---

## 🖥️ User Interface

The project uses **Gradio** to create a simple web-based interface.

The UI displays:

* Static-analysis report
* LLM-generated review
* Severity classification
* Recommended fixes

When executed in Google Colab, Gradio automatically generates a public URL for accessing the application.

Example:

```text id="d4m3es"
Running on public URL:
https://xxxxxxxx.gradio.live
```

---

## 📋 Sample Output

```text id="x03b9r"
========== STATIC ANALYSIS REPORT ==========

Flake8:
E231 missing whitespace after ','

Pylint:
Unused import os
Unused variable 'temp'

Bandit:
Possible hardcoded password

========== LLM REVIEW ==========

Issue: Missing Whitespace After Comma
Severity: Low
Fix: Add a space after the comma.

Issue: Unused Import
Severity: Medium
Fix: Remove the unused import.

Issue: Unused Variable
Severity: Medium
Fix: Remove the variable or use it.

Issue: Hardcoded Password
Severity: High
Fix: Store credentials in environment variables.
```

---

## 🔄 Workflow

```text id="mblvql"
         Source Code
                ↓
      Static Analysis Tools
                ↓
    (Flake8 / Pylint / Bandit)
                ↓
         Analysis Reports
                ↓
           LLM Review
                ↓
      Severity Classification
                ↓
       Suggested Fixes
                ↓
          Gradio UI
                ↓
         User Display
```

---

## 📚 Learning Outcomes

This project demonstrates:

* Static code analysis
* Security vulnerability detection
* LLM-assisted code review
* Prompt-based issue explanation
* Severity classification
* Gradio UI development
* Integration of AI and software engineering tools

---

## 🚀 How to Run

### Step 1: Install Gradio

```bash id="48pbyw"
pip install gradio
```

### Step 2: Open Google Colab

Create a new notebook.

### Step 3: Copy the Python Code

Paste the contents of:

```text id="wimrgr"
static_analysis_llm_ui.py
```

into a code cell.

### Step 4: Run the Program

Execute the notebook cell.

### Step 5: Open the Generated URL

Gradio will generate a public URL such as:

```text id="aqmfgd"
https://xxxxxxxx.gradio.live
```

Open the link to view the user interface.

---

## 👩‍💻 Author

**Dharshini A**

---

## 📌 Project Type

**Static Analysis + LLM Review + User Interface Integration**
