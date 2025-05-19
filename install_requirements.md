# E-Commerce-Analyse App - Installationsanleitung

Um die E-Commerce-Analyse App auf Ihrem System oder über GitHub zu installieren, benötigen Sie die folgenden Pakete:

## Benötigte Pakete

```
numpy>=1.20.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
streamlit>=1.12.0
plotly>=5.3.0
joblib>=1.1.0
imbalanced-learn>=0.8.0
xgboost>=1.5.0
lightgbm>=3.3.0
requests>=2.26.0
```

## Installation

### Lokale Installation

1. Erstellen Sie eine neue virtuelle Umgebung (empfohlen):
   ```
   python -m venv venv
   source venv/bin/activate  # Unter Windows: venv\Scripts\activate
   ```

2. Installieren Sie die benötigten Pakete:
   ```
   pip install numpy pandas matplotlib seaborn scikit-learn streamlit plotly joblib imbalanced-learn xgboost lightgbm requests
   ```

3. Starten Sie die App:
   ```
   streamlit run app.py
   ```

### Hosting auf Streamlit Cloud

1. Erstellen Sie einen Account auf [Streamlit Cloud](https://streamlit.io/cloud)
2. Erstellen Sie ein GitHub-Repository mit dem Code
3. Fügen Sie eine Datei `requirements.txt` mit den oben genannten Paketen hinzu
4. Verbinden Sie Ihr Repository mit Streamlit Cloud
5. Die App wird automatisch bereitgestellt und ist öffentlich zugänglich

## Hinweise

- Die App erstellt automatisch die benötigten Modellverzeichnisse und trainiert fehlende Modelle beim ersten Start
- Der UCI "Online Shoppers Purchasing Intention" Datensatz wird automatisch geladen