# Redrob AI Hackathon Submission

## Overview

This repository contains my submission for the Redrob AI Hiring Challenge.

The objective was to rank candidates based on their suitability for a Senior AI Engineer role by combining semantic similarity with structured candidate signals.

---

## Approach

### Semantic Matching
- Extracted the job description from the provided DOCX file.
- Converted candidate profiles into structured text.
- Used the SentenceTransformer model:
  - all-MiniLM-L6-v2
- Computed cosine similarity between the job description and each candidate profile.

### Structured Scoring
Additional signals were incorporated including:
- Years of experience
- Notice period
- Open-to-work status
- Recruiter response rate
- GitHub activity score

The final score combines semantic similarity with structured scoring.

---

## Tech Stack

- Python
- Sentence Transformers
- Pandas
- python-docx
- Google Colab

---

## Repository Structure

```
.
├── submission.csv
├── Redrob_AI_Hackathon.ipynb
└── README.md
```

---

## Output

The generated `submission.csv` contains:

- candidate_id
- rank
- score
- reasoning

---

## Author

Pankesh Sahu
