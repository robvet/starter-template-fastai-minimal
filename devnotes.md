# Dev Notes

## Create virtual environment (Python 3.11)
python3.11 -m venv .venv

## Activate
source .venv/bin/activate

## Install
pip install -r requirements.txt

## Run app (API + UI)
python -m uvicorn app.main:app --app-dir src --host 127.0.0.1 --port 8010
# open http://127.0.0.1:8010

## Run tests
pytest

If you keep port 8010, add it to the app prompt so the README and these notes agree:

- README run command: uvicorn app.main:app --host 127.0.0.1 --port 8010