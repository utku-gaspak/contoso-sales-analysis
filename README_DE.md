# Vertriebsanalyse Contoso (Retail Data) 📊
[![English](https://img.shields.io/badge/Lang-English-red)](README.md) [![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](analysis_notebook.ipynb)
## 📌 Projektüberblick
Dieses Projekt analysiert den **Contoso-Datensatz** (ein fiktiver Einzelhandels-Datensatz von Microsoft), um Umsatztrends, Kaufverhalten und Kundenbindung (Retention) zu untersuchen.

Ziel war es, einen realistischen Business-Intelligence-Workflow zu simulieren: von der Datenexploration bis zur Beantwortung komplexer Geschäftsfragen mithilfe von SQL.

## 🛠️ Tools & Technologien
* **SQL-Dialekt:** PostgreSQL
* **Angewandte Techniken:**
    * **Window Functions** (`RANK`, `LEAD`, `LAG`) für gleitende Durchschnitte und laufende Summen.
    * **CTEs (Common Table Expressions)** zur Strukturierung komplexer Abfragen.
    * **Datenaggregation** (`GROUP BY`) für Reporting-Zwecke.
    * **Kohortenanalyse** zur Untersuchung der Kundenbindung über die Zeit.

## 🔍 Wichtige Erkenntnisse (Insights)
* **Kundenbindung (Retention):** Analyse der Abwanderungsraten (Churn Rates) zeigte einen signifikanten Rückgang der Kundenaktivität nach den ersten 3 Monaten.
* **Umsatztrends:** Berechnung des gleitenden 3-Monats-Durchschnitts, um saisonale Schwankungen in den Verkaufsdaten zu glätten.
* **Kundensegmentierung:** Einteilung der Kunden in Segmente (High/Mid/Low Value) mittels Perzentilen, um gezielte Marketingstrategien zu ermöglichen.

## 🚀 Ausführung
Öffnen Sie die Datei `analysis_notebook.ipynb`, um die Schritt-für-Schritt-Logik einzusehen.
