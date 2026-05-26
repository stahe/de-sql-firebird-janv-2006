# Einführung in SQL mit dem DBMS Firebird

➡️ Verwandter Kurs: **[Einführung in SQL mit dem DBMS Firebird](https://stahe.github.io/de-sql-firebird-janv-2006/)**

## Überblick

Dieses Dokument ist eine Einführung in die Sprache **SQL (Structured Query Language)** in Verbindung mit dem **DBMS Firebird**.
Es überarbeitet und passt ein altes Lehrdokument an, das **1991 für Oracle** verfasst wurde und seinerseits weitgehend von der offiziellen Oracle-Dokumentation sowie dem Buch inspiriert war:

* *SQL – Einführung, Programmierung und Beherrschung*
  von **Christian Marée** und **Guy Ledant**, erschienen bei Eyrolles.  

SQL ist eine **Standard-Sprache, die zum Erstellen, Verwalten und Ausführen von Abfragen auf relationalen Datenbanken verwendet wird**.
Sie ist weitgehend unabhängig vom verwendeten Datenbankmanagementsystem (DBMS), auch wenn einige DBMS proprietäre Erweiterungen einführen. 

## Warum Firebird?

Die Beispiele in diesem Dokument verwenden das **DBMS Firebird**.
Diese Wahl ist durch eine in einem Lehrkontext besonders praktische Eigenschaft begründet: Eine Firebird-Datenbank kann **in einer einzigen Datei enthalten sein**.

Dies ermöglicht beispielsweise:

* das einfache Kopieren einer Datenbank auf einen **USB-Stick**
* die Verwendung auf **verschiedenen Computern** (zu Hause, an der Universität, im Labor)
* das Arbeiten ohne komplexe Infrastrukturen

## SQL-Kompatibilität

Obwohl die Beispiele für Firebird geschrieben sind, lassen sich die meisten mit anderen relationalen DBMS nachstellen, zum Beispiel:

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

Alle diese Systeme verwenden SQL, manchmal mit **produktspezifischen Varianten oder Erweiterungen**.

## Zielgruppe

Dieses Dokument richtet sich an:

* **Anfänger, die SQL lernen möchten**
* Personen, die **die Grundlagen der Sprache auffrischen** möchten

Es konzentriert sich auf das Erlernen der **Grundlagen von SQL**.

## Ausnahmen vom Anwendungsbereich

Einige Themen wurden bewusst ausgelassen:

* gespeicherte Prozeduren
* fortgeschrittene SQL-Programmierung
* SQL-API's
* DBMS-Administration

Das Ziel ist es, eine **klare und schrittweise Einführung in die Sprache SQL** zu bieten.

Serge Tahé, Januar 2006