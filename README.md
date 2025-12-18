# DevOps CI/CD Pipeline

Flask web app with CI pipeline (tests) and Docker build using GitHub Actions.

## Endpoints
- `/` returns a hello message
- `/health` returns JSON status

## Run locally
```bash
python -m venv .venv
# Windows:
.\.venv\Scripts\activate
pip install -r requirements.txt
python app.py
