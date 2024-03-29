# business-analytics-case-study

Cheat Sheets:

- [Python](https://github.com/FavioVazquez/ds-cheatsheets/blob/master/Python/Python_Crash_Course/Beginners-Python-Cheat-Sheet.pdfF)
- [Pandas](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Seaborn](https://images.datacamp.com/image/upload/v1676302629/Marketing/Blog/Seaborn_Cheat_Sheet.pdf)
- [Matplotlib](https://matplotlib.org/cheatsheets/)
- [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Link Präsi: [Präsi_Business_Analytics.pptx](https://fhbi-my.sharepoint.com/:p:/g/personal/tim_strulik_fhbi_onmicrosoft_com/EV1QVUrv73JBpa6JS5QQSeEBPm-4y6tKjFnK5epyjhhUjw?e=2MNd61)

# Arbeitspakete 29.11.2023

## Datenaufbereitung (Patrick)

- Spalten umbennen → snake_case, alle in Englisch
- Auf Duplikate
- Sinnvolle Datentypen einsetzen (jahr in preise bspw.)
- Preise an Regionstabelle joinen → dann Umsatz Gewinn etc. berechnen...

## Hypothesen/Fragen:

- Tim: Kundenbewertung hat Einfluss auf wirtschaftliche Performance?

  - Region
  - Marktplatz/Verkaufsart
- Moritz: Wie ist das Kaufverhalten?

  - Transaktionsanzahl pro Zeiteinheit (monatlich, wöchentlich) geht zurück?
  - Menge pro Transaktion wird weniger? Leute kaufen 5 Tablets statt 1
  - Kunden kaufen günstigere Modelle → Preis pro Produkt ist weniger
- Florian

  - Gewinn sinkt, weil Kosten steigen? → auf Regionen und Markplatz beziehen
  - Sind Stores ineffektiv? (auf Umsatz, menge, Gewinn etc. beziehen)
- Patrick: Hat die Downtime einen Einfluss auf die Verkäufe (Allgemein)?

  - Hat die Steigerung der Downtime in Region A und B zu einem Rückgang der Online-Verkäufe geführt?
  - Region C: Downtime sinkt um 1 %, steigen Online-Verkäufe? → in Zusammenhang mit Region D prüfen, hier steigt die Downtime um 1 %

# Arbeitspakete 6.12.2023

- Florian
  - Rücksprache mit Herrn Zeidler
    - Wie sehr sollen/dürfen wir bei Handlungsempfehlungen spekulieren?

## Graphen schön machen bzw. stehende Erkenntnisse

- Tim

  - Umsatz, Verkaufszahlen, Anzahl der Transaktionen und Kosten
  - Costumer Ratings, zeitliche Entwicklung und Marketplaces
  - Grundriss für die Präsentation überlegen
- Moritz

  - Menge pro Transaktion sinkt leicht

## Weitergehende Hypothesen/Fragen

- Patrick

  - Tablet Basic
    - Weitere Grafiken erstellen
    - Lineare Regression
    - Simulationen erstellen
- Florian

  - Vergleich der verschiedenen Modelle
    - Gewinnmargen
    - Verkaufszahlen & Erklärung
    - Nach Markplatz aufschlüsseln
      - Sinken die Gewinne des Stores wegen bestimmter Modelle?
- Moritz

  - Discounts
    - Marketplace relativ
    - Steigt die Anzahl an verkauften Tablets bei Discounts im Vergleich zu keinem Discount?

# Präsentationsvorbereitung am 18.12. 9:30 Uhr

Link Präsi: [Präsi_Business_Analytics.pptx](https://fhbi-my.sharepoint.com/:p:/g/personal/tim_strulik_fhbi_onmicrosoft_com/EV1QVUrv73JBpa6JS5QQSeEBPm-4y6tKjFnK5epyjhhUjw?e=2MNd61)

- Hypothesen

  - Florian & Tim
  - Stores sind ineffektiv
    - Florian
    - Regionen und die Markplätze zum Vergleich an
    - Kosten

    - Tim
    - Produkte und damiteinhergehend Preise

    - Handlungsempfehlung: Weitergehende Kostenanalyse, Preise erhöhen oder Stores schließen (nur in bestimmten Regionen)

  - Patrick & Moritz
    - Moritz
    - Weitergehende Analyse der Regionen und Marktplätze

    - Patrick
    - Zeitliche Entwicklung der Kennzahlen (Verkaufszahlen, Gewinn, Umsatz, Kosten, Preise, Customer Ratings Anzahl Transaktionen)
    - Verluste weiter analysieren

    - Handlungsempfehlung: Kundenbefragung, Preise erhöhen, Modell nur in bestimmten Marktplätzen anbieten oder Modell abschaffen

# Notebookerstellung

- Paketimporten
- Datenaufbereitung (main)
- Gesamtübersicht aus der Präsentation (tim/präsi_sandbox)

- Gewinn sinkt, weil Kosten steigen? → auf Regionen und Markplatz beziehen
- Sind Stores ineffektiv? (auf Umsatz, menge, Gewinn etc. beziehen) (florian/kostenanalyse)
- Discounts (moritz/sandbox1)
- Marketplace relativ
- Steigt die Anzahl an verkauften Tablets bei Discounts im Vergleich zu keinem Discount?
- Produkte und damiteinhergehend Preise (tim/analyse_stores_produkte_sandbox)

- Vergleich der verschiedenen Modelle (florian/analyse_vergleich_modelle)
  - Gewinnmargen
  - Verkaufszahlen & Erklärung
    - Nach Markplatz aufschlüsseln
- Tablet Basic (patrick/analyse_tabletbasic)
  - Weitere Grafiken erstellen
  - Lineare Regression
  - Simulationen erstellen+
- Wie ist das Kaufverhalten? (moritz/sanbox1)
  - Transaktionsanzahl pro Zeiteinheit (monatlich, wöchentlich) geht zurück?
  - Menge pro Transaktion wird weniger? Leute kaufen 5 Tablets statt 1
  - Kunden kaufen günstigere Modelle → Preis pro Produkt ist weniger

- Kundenbewertung hat Einfluss auf wirtschaftliche Performance? (tim/analyse_rating_sandbox)
  - Region
  - Marktplatz/Verkaufsart

- Hat die Downtime einen Einfluss auf die Verkäufe (Allgemein)? (patrick/analyse_downtime)
  - Hat die Steigerung der Downtime in Region A und B zu einem Rückgang der Online-Verkäufe geführt?
  - Region C: Downtime sinkt um 1 %, steigen Online-Verkäufe? → in Zusammenhang mit Region D prüfen, hier steigt die Downtime um 1 %

- Fazit mit entsprechenden Handlungsempfehlungen