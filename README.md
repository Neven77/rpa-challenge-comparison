# RPA Challenge Comparison - No-Code vs. Low-Code vs. High-Code

Academic certificate project in CAS AI in Process Mining (HWZ).

German version: [README_DE.md](README_DE.md)

## 1. Project Goal

This project compares three automation approaches using the same benchmark task from [rpachallenge.com](https://rpachallenge.com/):

1. The goal is to build a workflow that inputs spreadsheet data into the form fields on screen.
2. Field positions change after each submission across 10 rounds, so selectors and logic must stay robust.
3. The official timer starts when clicking Start; before that, trial submissions are possible.

The comparison focuses on speed, sustainability, maintainability, and entry barrier.

## 2. Compared Technologies

| Approach | Tool |
| --- | --- |
| No-Code | Power Automate Desktop |
| Low-Code | UiPath Studio |
| High-Code | Python |

## 3. Evaluation Criteria

The academic evaluation is based on a criteria catalog and utility value analysis. Core criteria:

- Implementation speed
- Sustainability
- Maintainability
- Entry barrier

## 4. Results Summary

Each approach has clear strengths and trade-offs. The best choice depends on context, team setup, available skills, and long-term requirements.

No absolute winner is claimed here unless fully documented metrics are provided.

## 5. Python Implementation

Only the Python implementation is included in this repository.

Current implementation artifact:

- `rpa_challenge.ipynb`

### Quick Start

Using a virtual environment (`.venv`) is strongly recommended for this project.

1. Create and activate `.venv`:

```bash
python -m venv .venv
```

PowerShell (Windows):

```powershell
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter and open the notebook:

```bash
jupyter notebook rpa_challenge.ipynb
```

4. In VS Code/Jupyter, select the `.venv` kernel for `rpa_challenge.ipynb`.

### Prerequisites

- Google Chrome must be installed locally.
- No separate Chrome extension is required.
- No manual ChromeDriver download is required because `webdriver-manager` fetches the matching driver automatically.

### Notes

- The notebook reads the input file from `data/challenge.xlsx`.
- If `data/challenge.xlsx` is missing, the notebook auto-downloads `challenge.xlsx` and stores it in `data/`.

This repository already includes a `requirements.txt` file.

## 6. Why no UiPath / Power Automate files included

UiPath and Power Automate were evaluated as part of the academic project.
Only the Python implementation is included in this repository.

## 7. Author

Neven Odrljin  
https://odrljin.ch

## License

MIT
