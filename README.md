# Resume-job-matching

A prototype resume–job matching system developed as part of the paper Group-Aware Resume–Job Matching: A Comparative Study of Text Representation Methods on a Cleaned Large-Scale Recruitment Dataset

The system matches candidate profiles to job descriptions using TF-IDF and SBERT cosine similarity with group-aware filtering. Candidates are only compared to jobs within the same position group.
# Files

app.py — Streamlit web application
matcher.py — TF-IDF and SBERT matching logic
utils.py — File parsing and text cleaning utilities
requirements.txt — Required Python packages
# How to Run

pip install -r requirements.txt
streamlit run app.py

The application loads the following cleaned datasets from HuggingFace at startup:

Job descriptions: https://huggingface.co/datasets/handeyilmaz/job-descriptions-ready-to-use

Candidate profiles: https://huggingface.co/datasets/handeyilmaz/candidate-profiles-ready-to-use
