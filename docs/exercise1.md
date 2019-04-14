# Exercise 1

## Task
- Fahrzeugdatensatz ist mit Hilfe statistischer Standardfunktionen zu analysieren, interpretieren und ggfs. bereigen
- Visuelle Darstellungsarten in verschiedenen Diagrammen, um wichtige Zusammenhänge zu visualisieren
- Kommentare, um interessante Erkenntnisse festzuhalten

## Crisp-DM

### Phase: Data Unterstanding
- Welche Daten liegen vor?
  - Fahrzeugdaten, in dem verschiedene Merkmale von Fahrzeugen genannt werden
  - Format CSV-Datei
  - Anzahl von Instanzen: 398
  - Anzahl Attribute: 9 (inkl. der Klassenatttribute
  - Attribute:
    1. mpg:           continuous
    2. cylinders:     multi-valued discrete
    3. displacement:  continuous
    4. horsepower:    continuous
    5. weight:        continuous
    6. acceleration:  continuous
    7. model year:    multi-valued discrete
    8. origin:        multi-valued discrete
    9. car name:      string (unique for each instance)
  - Zusatz:
    - horsepower has 6 missing attributes

- Wie sehen diese Daten aus? Könnte es Probleme mit den Daten geben?
  - im csv format
  - fehlende Attribute bei mpg (NA) 
    - könnten zu Probleme führen
    - evlt ersetzen durch anderen Wert? 0?
  - horsepower fehlen Attribute?
  - Attribute getrennt durch Tab
  - Zeile = Datensatz
  - "." am Ende mancher Attributwerte
- Kann man "auf den ersten Blick" Zusammenhänge erkennen?
- Wie können beispielhafte Antworten oder Ergebnisse aussehen? 

### Phase: Data Preparation
- Können die Daten in der vorliegenden Form verwendet werden?
- Wie können diese vorverarbeitet werden, um sie zu verwenden?

