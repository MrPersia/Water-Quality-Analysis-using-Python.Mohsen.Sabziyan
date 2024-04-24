# Water-Quality-Analysis-using-Python.Mohsen.Sabziyan
# Wasserqualitätsanalyse mit maschinellem Lernen

Dieses Repository enthält Code zur Analyse von Wasserqualitätsdaten mithilfe von Techniken des maschinellen Lernens. Das Ziel dieses Projekts ist es, die Trinkwasserqualität basierend auf verschiedenen Wasserqualitätsparametern vorherzusagen.

## Datensatz

Der im Projekt verwendete Datensatz befindet sich in der Datei `water_potability.csv`. Er enthält die folgenden Spalten:

- `ph`: pH-Wert des Wassers
- `Hardness`: Härte des Wassers
- `Solids`: Gesamtfeststoffe (TDS) in ppm (Teile pro Million)
- `Chloramines`: Menge an Chloraminen in ppm
- `Sulfate`: Menge an Sulfat in ppm
- `Conductivity`: Elektrische Leitfähigkeit des Wassers
- `Organic_carbon`: Menge an organischem Kohlenstoff in ppm
- `Trihalomethanes`: Menge an Trihalomethanen in ppm
- `Turbidity`: Trübung des Wassers

Die Zielvariable ist `Potability`, die angibt, ob das Wasser trinkbar (1) ist oder nicht (0).

## Einrichtung und Verwendung

### Anforderungen

Um den Code auszuführen, benötigen Sie Python auf Ihrem System sowie die folgenden Bibliotheken:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- pycaret

Fazit
Basierend auf den Auswertungsergebnissen hat der Random Forest Classifier am besten abgeschnitten mit einer Genauigkeit von 0.678 und einer AUC von 0.684. Weitere Optimierungen und Merkmalsextraktion können untersucht werden, um die Leistung des Modells zu verbessern.
