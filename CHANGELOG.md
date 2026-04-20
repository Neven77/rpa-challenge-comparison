# Changelog

## 2026-04-20

- Updated `rpa_challenge.ipynb` to work with current Selenium versions (`Service`, `Options`, `WebDriverWait`).
- Added robust Excel loading in notebook:
  - Uses local `challenge.xlsx` if present.
  - Downloads `challenge.xlsx` automatically (with headers) when missing.
- Added final cleanup cell (`browser.quit()`).
- Added `requirements.txt` with all Python dependencies.
- Updated `README.md` and `README_DE.md` with concise setup and `.venv` recommendation.
- Updated notebook and docs to use `data/challenge.xlsx` as primary input path.
- Added `.venv/` to `.gitignore` so the local virtual environment is not committed.
- Clarified in README files that Chrome itself is required, no extra Chrome add-on is needed, and the legacy notebook is incompatible with current Selenium APIs.
