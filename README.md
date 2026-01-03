**Multi-Factor Return Forecasting für Microsoft (2010–2019)**

In diesem Projekt modelliere ich die 5-Tage-Vorwärts-Renditen der Microsoft-Aktie anhand verschiedener Aktien-, Währungs- und Makro-Indikatoren.
Ziel: Wie unterschiedliche finanzielle Faktoren kurzfristige Kursbewegungen beeinflussen und wie verschiedene Modellansätze im Vergleich abschneiden.

Zum Einsatz kommen unter anderem:
1. Lineare Regression (Basis-Modell)
2. Decision Tree Regressor (nichtlineares Modell)
3. LSTM-Neuronales Netzwerk (sequenzbasiertes Deep-Learning-Modell)

Dieses Notebook umfasst:
1. Datenextraktion aus Yahoo Finance und FRED
2. Feature Engineering auf Basis mehrerer Assets und Finanzindikatoren
3. Explorative Datenanalyse (Korrelationsmatrix, Scatterplots, saisonale Dekomposition)
4. Training und Evaluation der Modelle mittels MSE (Train vs. Test)
5. Visualisierung von tatsächlichen vs. prognostizierten Renditeverläufen
6. Interpretation der Ergebnisse und Diskussion der Grenzen von Finanzprognosen
