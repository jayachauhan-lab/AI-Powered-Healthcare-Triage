# AI-Powered-Healthcare-Triage

This demo shows how a  neural network can understand healthcare patient messages by predicting both the intent (what the patient needs) and a satisfaction/urgency score (how urgent or emotional the request is).
This helps healthcare organizations triage faster, automate simple tasks, and escalate urgent or anxious cases to human staff immediately


------------------
## Features

-----------

**Project Structure**

/AI-Powered-Healthcare-Triage


├── healthcare.py

├── healthcare.csv

├── README.md

-------------
 ## Requirements
1. Python 3.8+

Install Python if not already installed.



2. Install dependencies using pip:

```bash
pip install scikit-learn numpy
```

---

## Installation

Install any Python dependencies (none beyond the standard library are required).

Ensure healthcare.csv is in the same directory as healthcare.py.

## How to Run

Run the script:
```bash
python healthcare.py
```

The script will:

Overall classification accuracy

Regression R² and RMSE

Two example predictions with both AI tasks clearly separated

Combined value explanation

## Dataset

Short healthcare-related user messages (text)

An associated intent label (classification target)

A satisfaction/urgency score (regression target, 0-10 scale)






