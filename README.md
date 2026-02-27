# FastAPI Todo API (Infinity Developer)

A tiny FastAPI app with automated tests and GitHub Actions CI.

## Run locally

```bash
# 1) (Optional) Create a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 2) Install deps
pip install -r requirements.txt

# 3) Start the API (http://127.0.0.1:8000)
uvicorn app.main:app --reload
