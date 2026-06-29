# 🤖 AI-Powered Semantic Candidate Ranking System

### Redrob AI Hiring Challenge Submission

> An intelligent AI-powered candidate ranking system that combines semantic understanding with structured candidate signals to identify the most relevant applicants for a Senior AI Engineer role.

---

# 📌 Project Overview

Traditional recruitment systems rely heavily on keyword matching, often overlooking highly qualified candidates due to differences in wording.

This project introduces a **Semantic Candidate Ranking System** that leverages Natural Language Processing (NLP) and transformer-based embeddings to understand the true meaning of resumes and rank candidates based on overall relevance.

The system processes over **100,000 candidate profiles**, compares them against the target Job Description using semantic similarity, incorporates additional structured hiring signals, and generates a submission-ready ranked candidate list.

---

# 🎯 Challenge Objective

Develop an AI-powered ranking system capable of:

- Understanding candidate resumes semantically
- Comparing resumes with a Job Description
- Ranking candidates based on overall relevance
- Generating a submission-ready CSV file

---

# 🚀 Solution Pipeline

```text
Job Description
        │
        ▼
Text Extraction
        │
        ▼
Resume Preprocessing
        │
        ▼
Sentence Transformer
(all-MiniLM-L6-v2)
        │
        ▼
Semantic Embeddings
        │
        ▼
Cosine Similarity
        │
        ▼
Structured Candidate Scoring
        │
        ▼
Final Weighted Score
        │
        ▼
Ranked Candidate List
        │
        ▼
submission.csv
```

---

# 🧠 Semantic Matching

Instead of relying solely on keyword matching, the system converts both the Job Description and candidate resumes into dense vector embeddings using the **Sentence Transformer** model:

- all-MiniLM-L6-v2

Semantic similarity is then calculated using **Cosine Similarity**, allowing the system to identify candidates with relevant skills even when different terminology is used.

---

# 📊 Structured Candidate Scoring

To improve ranking quality, semantic similarity is combined with additional structured hiring signals:

- Years of Experience
- Notice Period
- Open-to-Work Status
- Recruiter Response Rate
- GitHub Activity Score

The final ranking score is computed using a weighted combination of semantic relevance and structured candidate signals.

---

# ⚙️ Technology Stack

- Python
- Sentence Transformers
- all-MiniLM-L6-v2
- Pandas
- python-docx
- Google Colab

---

# 📂 Repository Structure

```text
.
├── Redrob_AI_Hackathon.ipynb
├── submission.csv
└── README.md
```

---

# 📈 Output

The generated **submission.csv** contains the following columns:

| Column | Description |
|----------|-------------|
| candidate_id | Unique candidate identifier |
| rank | Final candidate ranking |
| score | Overall ranking score |
| reasoning | AI-generated reasoning for the assigned rank |

---

# ✨ Key Highlights

- ✅ AI-Powered Semantic Resume Matching
- ✅ Transformer-Based Embedding Generation
- ✅ Cosine Similarity Ranking
- ✅ Structured Candidate Scoring
- ✅ Processes **100,000+ Candidate Profiles**
- ✅ Fully Reproducible Pipeline
- ✅ Submission-Ready CSV Generation

---

# 🔮 Future Improvements

- Cross-Encoder Re-ranking
- Explainable AI Recommendations
- Recruiter Dashboard
- Multi-Job Candidate Matching
- LLM-Based Resume Parsing
- Cloud Deployment
- REST API Integration

---

# 👨‍💻 Author

**Pankesh Sahu**

AI & Software Engineering Enthusiast

GitHub: https://github.com/Pankesh2227E

---

### ⭐ If you found this project interesting, consider giving the repository a star!