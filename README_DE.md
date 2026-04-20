# RPA Challenge Comparison - No-Code vs. Low-Code vs. High-Code

Zertifikatsarbeit im CAS AI in Process Mining (HWZ).

Englische Version: [README.md](README.md)

## 1. Projektziel

Dieses Projekt vergleicht drei Automatisierungsansätze anhand derselben Benchmark-Aufgabe von [rpachallenge.com](https://rpachallenge.com/):

1. Ziel ist ein Workflow, der Daten aus einer Tabelle in Formularfelder auf dem Bildschirm einträgt.
2. Die Positionen der Felder ändern sich nach jeder Übermittlung über 10 Runden, daher muss die Erkennung robust bleiben.
3. Die offizielle Zeitmessung startet mit dem Start-Button; davor sind Testübermittlungen ohne Strafe möglich.

Der Vergleich fokussiert auf Geschwindigkeit, Nachhaltigkeit, Wartbarkeit und Einstiegshürde.

## 2. Verglichene Technologien

| Ansatz | Tool |
| --- | --- |
| No-Code | Power Automate Desktop |
| Low-Code | UiPath Studio |
| High-Code | Python |

## 3. Bewertungskriterien

Die akademische Bewertung basiert auf einem Kriterienkatalog und einer Nutzwertanalyse. Kernkriterien:

- Umsetzungsgeschwindigkeit
- Nachhaltigkeit
- Wartbarkeit
- Einstiegshürde

## 4. Ergebnisübersicht

Jeder Ansatz hat klare Stärken und Zielkonflikte. Die beste Wahl hängt vom Kontext, vom Team, vom vorhandenen Know-how und von den langfristigen Anforderungen ab.

Es wird kein absoluter Gewinner behauptet, solange keine vollständig dokumentierten Messwerte vorliegen.

## 5. Python-Implementierung

In diesem Repository ist nur die Python-Implementierung enthalten.

Aktuelles Implementierungsartefakt:

- `rpa_challenge.ipynb`

### Schnellstart

Ein virtuelles Environment (`.venv`) wird für dieses Projekt klar empfohlen.

1. `.venv` erstellen und aktivieren:

```bash
python -m venv .venv
```

PowerShell (Windows):

```powershell
.\.venv\Scripts\Activate.ps1
```

2. Abhängigkeiten installieren:

```bash
pip install -r requirements.txt
```

3. Jupyter starten und Notebook öffnen:

```bash
jupyter notebook rpa_challenge.ipynb
```

4. In VS Code/Jupyter den `.venv`-Kernel für `rpa_challenge.ipynb` auswählen.

### Voraussetzungen

- Google Chrome muss lokal installiert sein.
- Eine separate Chrome-Erweiterung ist nicht erforderlich.
- Ein separater ChromeDriver-Download ist nicht erforderlich, da `webdriver-manager` den passenden Treiber automatisch bezieht.

### Hinweise

- Das Notebook liest die Eingabedatei aus `data/challenge.xlsx`.
- Falls `data/challenge.xlsx` fehlt, lädt das Notebook `challenge.xlsx` automatisch herunter und speichert sie in `data/`.

Dieses Repository enthält bereits eine `requirements.txt`.

## 6. Warum keine UiPath-/Power-Automate-Dateien enthalten sind

UiPath und Power Automate wurden im Rahmen der akademischen Arbeit bewertet.
In diesem Repository ist bewusst nur die Python-Implementierung enthalten.

## 7. Autor

Neven Odrljin  
https://odrljin.ch

## Lizenz

MIT
