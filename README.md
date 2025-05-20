# E-Commerce Kaufabsicht Analyse

Eine leistungsstarke Anwendung zur Analyse und Vorhersage von Kaufabsichten im E-Commerce-Bereich, basierend auf dem UCI "Online Shoppers Purchasing Intention" Datensatz.

![E-Commerce Analyse App](screenshot.png)

## Überblick

Diese Anwendung bietet fortschrittliche Analysen und Vorhersagen für das Kaufverhalten von E-Commerce-Kunden. Sie kombiniert exploratorische Datenanalyse mit Machine Learning, um Kaufmuster zu identifizieren und Kaufwahrscheinlichkeiten vorherzusagen.

### Hauptfunktionen:

- **Datenübersicht**: Umfassende Visualisierungen und statistische Analysen
- **Maschinelles Lernen**: Mehrere Vorhersagemodelle (RandomForest, LogReg, DecisionTree)
- **Interaktive Vorhersage**: Sofortige Kaufabsichtsvorhersagen für neue Besucher
- **F9Tuned-Modellsystem**: Optimiertes Ensemble-Modell mit verschiedenen Algorithmen

## Installation

Eine detaillierte Installationsanleitung finden Sie in der [Installationsanleitung](install_requirements.md).

## Datensatz

Die Anwendung verwendet den UCI "Online Shoppers Purchasing Intention" Datensatz, der folgende Merkmale enthält:

- **Seitentyp-Metriken**: Administrative, Informational, ProductRelated Seiten und deren Besuchsdauer
- **Google Analytics-Metriken**: BounceRates, ExitRates, PageValues
- **Kontextuelle Merkmale**: SpecialDay (Nähe zu besonderen Tagen wie Valentinstag)
- **Besuchermerkmale**: OperatingSystems, Browser, Region, TrafficType, VisitorType, Weekend
- **Zielvariable**: Revenue (Kaufabschluss ja/nein)

## Modellperformance

Das optimierte F9Tuned RandomForest-Modell erreicht eine Accuracy von 89,7% und einen F1-Score von 61,5% für die Kaufabsichtsvorhersage.

## Technologie-Stack

- Python 3.11+
- Streamlit für die interaktive Benutzeroberfläche
- Scikit-learn, XGBoost, LightGBM für maschinelles Lernen
- Pandas für Datenverarbeitung
- Matplotlib, Seaborn und Plotly für Visualisierungen

## Beitragen

Beiträge sind willkommen! Bitte lesen Sie unsere Beitragsrichtlinien, bevor Sie Pull Requests einreichen.

## Lizenz

Das verwendete UCI Datenset steht unter einer CC BY 4.0 Lizenz
https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

## Danksagungen

- UCI Machine Learning Repository für den "Online Shoppers Purchasing Intention" Datensatz
- Alle Mitwirkenden, die zu diesem Projekt beigetragen haben

## Weiteres 
Dieses README Dokument wurde mit Hilfe von ChatGPT generiert und manuell angepasst
