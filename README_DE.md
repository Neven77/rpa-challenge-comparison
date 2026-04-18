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

Lokaler Start (Jupyter):

```bash
pip install -r requirements.txt
jupyter notebook rpa_challenge.ipynb
```

Falls die Abhängigkeiten noch nicht final sind, werden sie später in `requirements.txt` ergänzt.

## 6. Warum keine UiPath-/Power-Automate-Dateien enthalten sind

UiPath und Power Automate wurden im Rahmen der akademischen Arbeit bewertet.
In diesem Repository ist bewusst nur die Python-Implementierung enthalten.

Optionale Exporte können später in separaten Ordnern ergänzt werden:

- `uipath/`
- `powerautomate/`
- `docs/` (Kriterienkatalog, Nutzwertanalyse, Abschlussdokumente)

## 7. Autor

Neven Odrljin  
https://odrljin.ch

## Lizenz

MIT
