# sakila-analysis-project
Description: “SQL + DuckDB analysis of Sakila DVD rental data”
# Lab 1 – SQL: DVD Rental Analysis

## Beskrivning
Detta projekt handlar om att analysera DVD-uthyrningsdata från Sakila-databasen.  
Syftet är att migrera databasen från SQLite till DuckDB, utföra SQL- och Pandas-analyser, skapa visualiseringar och presentera insikter för “The Manager”.

---

## Projektstruktur
SAKILA-Analysis-project/
│
├── data/
│ ├── sqlite-sakila.db # Original SQLite-databas
│ └── sakila.duckdb # DuckDB-fil efter migration
│
├── notebooks/ # Jupyter Notebook med analyser
│ └── sakila_analysis.ipynb # EDA och visualiseringar
│
├── scripts/ # Script för att ladda databasen
│ └── load_sakila_duckdb.py
│
├── video/ # Projektpresentation (valfritt)
│ └── lab-presentation.mp4
│
└── README.md # Denna fil

---

## Installation och krav

1. Klona repot:
```bash
git clone https://github.com/<Salah-Ud-Din01>/dvd_rental_project.git

pip install -r requirements.txt
python scripts/load_sakila_dlt.py

