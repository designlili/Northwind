# Northwind
Rebuild and analysis of the Northwind dataset using PostgreSQL. Includes database design, CSV import, and 
SQL queries for sales, customers, and products. Enhanced with views, functions, and triggers to implement business logic.

# Northwind SQL Projekt

Dieses Projekt analysiert den Northwind-Datensatz mit PostgreSQL.

## Inhalt

- Erstellung aller Tabellen
- Import der CSV-Daten
- Verknüpfung der Tabellen mit Primary Keys und Foreign Keys
- SQL-Abfragen zur Datenanalyse
- Views
- Funktion zur Berechnung des Bestellwerts
- Trigger zur automatischen Lagerreduzierung

## Datenbank

Verwendet wurde:

- PostgreSQL
- DBeaver

## Dateien

- `northwind_setup.sql`  
  Erstellt alle Tabellen und importiert die CSV-Dateien.

- `queries_auswertung.sql`  
  Enthält die Antworten auf die Analysefragen.

- `views_functions_trigger.sql`  
  Enthält Views, Funktion und Trigger.

- `data/`  
  Enthält die CSV-Dateien des Northwind-Datensatzes.

## Analysefragen

Beantwortet wurden unter anderem:

1. Welche Produkte wurden verkauft?
2. Welche Produkte waren auf Lager?
3. Welche Produkte sind am teuersten und günstigsten?
4. Welcher Kunde hat am meisten gekauft?
5. Welcher Verkäufer hatte die meisten Geschäfte?
6. Welche Entwicklung gab es in den Jahren 1996 bis 1998?

## Datenquelle

Northwind-Datensatz von:

https://github.com/pawlodkowski/northwind_data_clean
