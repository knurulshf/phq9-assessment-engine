# PHQ-9 Assessment Engine

A Python implementation of the **Patient Health Questionnaire-9 (PHQ-9)** screening tool.

This project calculates PHQ-9 scores, classifies symptom severity, validates questionnaire responses, and generates a structured screening summary. It was developed as part of my journey in learning Python and building healthcare software.

> **Disclaimer**
>
> This project is intended for educational purposes only. It is not a diagnostic tool and should not replace clinical judgment or professional medical assessment.

---

## Features

- Calculate the total PHQ-9 score
- Classify PHQ-9 severity
- Flag positive responses on PHQ-9 Item 9 for clinical review
- Validate questionnaire completeness and response values
- Generate a formatted screening summary
- Modular, well-documented Python implementation

---

## Project Structure

```
phq9-assessment-engine/
│
├── phq9.py
├── main.py
├── README.md
└── .gitignore
```

---

## Example

### Input

```python
scores = [2, 3, 1, 0, 2, 1, 3, 0, 2]
```

### Output

```
==============================
PHQ-9 SCREENING SUMMARY
==============================

PHQ-9 Score: 14

Severity: Moderate

Clinical Review:
Positive response on PHQ-9 Item 9. Clinical review recommended.

Disclaimer:
This is a screening result only and does not establish a diagnosis.
```

---

## Learning Objectives

This project demonstrates fundamental Python programming concepts, including:

- Functions
- Lists
- Conditional statements
- Loops
- Input validation
- Modular program design
- Documentation using docstrings

---

## Future Development

This project is the first component of a larger mental health assessment system. Planned improvements include:

- GAD-7 assessment module
- Patient information management
- Combined PHQ-9 and GAD-7 reports
- Streamlit web application
- AI-assisted patient summary generation
- Mental health assessment and triage prototype

---

## Author

**Khansa Nurul Shafiyah**