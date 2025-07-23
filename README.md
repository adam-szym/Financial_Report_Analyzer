# Financial Report Analyzer (MVP)

A Jupyter notebook that uses LLMs + semantic search to summarize and compare key numbers and trends from banks’ earnings releases (PDF/TXT) — in seconds.

---

## Who’s it for?
- **Analysts**
- **Journalists**
- **Portfolio Managers**
- **Students**

Anyone who wastes hours reading financial reports.

---

## What does it do?
- Extracts and summarizes key metrics (e.g., revenue, net income, ROE) across quarters, business units, and companies.
- Lets you query, compare, and get plain-English output for banks’ financial reports — instantly.

---

## Requirements

- Jupyter Notebook / JupyterLab / JupyterHub
- Python 3.x (see `requirements.txt` or below for dependencies)

---

## Setup

1. **Clone/download this repo.**
2. **Put your bank earnings reports** (`.pdf` or `.txt`) into the `./financial_reports/` folder.  
   Filenames: `JPM_Q1_2024.pdf`, `GS_Q2_2024.txt`, etc.
3. **Open** `Financial_Report_Analyzer_MVP_2025.ipynb` in Jupyter.
4. **Run all cells** (top to bottom, or “Run All”).
5. When prompted, **type your query** (e.g., “Q1 2024 net income”, “compare Q2/Q3”, etc.).
6. **See the instant summary and matched numbers!**

---

## Features

- Query by company/quarter/unit
- Single-quarter, pairwise, or multi-quarter comparison
- Plain-English, analyst-style output
- Bullet-point summary + extracted key numbers

---

## Installation / Dependencies

- Python 3.9+
- `pandas`
- `PyPDF2`
- `langchain`
- `openai`
- *(Add your exact list or point to `requirements.txt`)*

---

## Known Limitations / To-Do

- Only tested on a few banks (add your own reports!)
- Currency/formatting extraction is basic (work in progress)
- **UI coming soon**

---

## Credits / Contact

Made by **Adam Szymczyk**  
[LinkedIn](https://www.linkedin.com/in/adam-szymczyk-724367263/)  
adam.szymczyk2004@gmail.com

