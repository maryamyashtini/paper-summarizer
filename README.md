# 🧠 Research Paper Summarizer Using GPT-4o and PDF Parsing

## 📝 Overview

This project provides a Python-based solution to **automatically summarize research papers (PDFs)** using **OpenAI's GPT-4o-mini model**. The system downloads the research paper from a provided URL, extracts its text using `PyPDF2`, and uses GPT to generate a concise, human-readable summary while ignoring complex mathematical formulas.

The example demonstrated in this notebook uses the paper:  
**"Bregman Operator Splitting with Variable Stepsize for Total Variation Image Reconstruction"**  
[Link to the paper](https://people.clas.ufl.edu/hager/files/BOSVS.pdf)

---

## 🚀 Features

- ✅ Automatically download PDFs from a URL.
- ✅ Extract text from research papers using `PyPDF2`.
- ✅ Summarize lengthy research papers with **OpenAI GPT-4o-mini**.
- ✅ Removes mathematical formulas from summaries for clearer understanding.
- ✅ Clean, reusable functions for easy extension.

---

## 🛠️ Tech Stack / Libraries Used

- Python 3.11+
- `requests`
- `openai`
- `dotenv`
- `PyPDF2`
- `BeautifulSoup` (imported but not used in this notebook — can be removed)
- Jupyter Notebook / Jupyter Lab

---

## ⚙️ How to Run This Project

1. **Clone the Repository**:
   ```bash
   git clone git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. pip install -r requirements.txt
4. OPENAI_API_KEY=sk-proj-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
5. jupyter lab
