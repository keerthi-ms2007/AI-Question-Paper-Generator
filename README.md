# AI Question Paper Generation System

Internship Project - AI-Powered Question Paper Generator built with Python & Streamlit.

It auto-generates question papers from syllabus using RAG, Bloom Taxonomy, difficulty balancing, duplicate detection, moderation workflow, and PDF export with answer key.

## Features
- Paper Blueprint Builder (Subject, Topic, Marks, Question Mix)
- RAG-Based Generation - Grounded in Syllabus
- Bloom Taxonomy Coverage (Remember to Create)
- Difficulty Balancing (Easy / Medium / Hard)
- Deduplication vs Past Papers
- Moderation Queue (Draft -> Approve / Reject -> Final)
- What-If Simulator (Predict Avg Score)
- PDF Export - Question Paper + Answer Key
- Analytics Dashboard & Audit Logs

## Tech Stack
Python, Streamlit, Pandas, Plotly, ReportLab

## How to Run
pip install -r requirements.txt
python -m streamlit run app.py

## Dataset
subjects.csv, syllabus.csv, past_papers.csv
