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

Run locally (Jupyter):

```bash
pip install -r requirements.txt
jupyter notebook rpa_challenge.ipynb
```

If requirements are not finalized yet, add them later to `requirements.txt`.

## 6. Why no UiPath / Power Automate files included

UiPath and Power Automate were evaluated as part of the academic project.
Only the Python implementation is included in this repository.

Optional exports can be added later in dedicated folders:

- `uipath/`
- `powerautomate/`
- `docs/` (for criteria catalog, utility value analysis, and final report assets)

## 7. Author

Neven Odrljin  
https://odrljin.ch

## License

MIT
