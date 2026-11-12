# Salary Prediction

Vorhersage des Gehalts von Angestellten aus Alter, Geschlecht, Abschluss, Jobtitel und Berufserfahrung.

Gruppenprojekt mit Adam, Dardan und Thies im Kurs **Data Science 1** (1. Semester, Bachelor Künstliche Intelligenz, HAW Landshut, WiSe 2024/25).

## Vorgehen

Aufgebaut nach CRISP-DM:

1. Analyseziel und Datenüberblick
2. Datenbereinigung
3. Visualisierung
4. Train-Test-Split
5. Preprocessing
6. Modelle: Lineare Regression und k-Nearest-Neighbors mit Suche nach dem besten k
7. Vergleich und Beurteilung der Modelle

## Inhalt

| Datei | Inhalt |
|---|---|
| `salary_prediction.ipynb` | das Notebook mit Analyse und Modellen |
| `datasets/salary.csv` | der Datensatz |
| `datasets/salary.txt` | Beschreibung der Spalten |

## Ausführen

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook salary_prediction.ipynb
```
