# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Lehrende | Sie bestimmen, welche Termine, ob Sprechstunde oder Prüfungstermin |
| Studierende | Sie bestimmen, wie einfach und schnell eine Buchung gehen muss |
| Sekretariate | Sie brauchen einen Überblick und müssen Termine im Auftrag von Lehrenden ändern oder absagen können |
| Rechenzentrum | Es stellt das Hochschulkonto bereit und betreibt das System, daraus folgen Anforderungen an Anmeldung, Betrieb und Sicherheit |
| Datenschutzbeauftragter | Legt fest, welche personenbezogenen Daten gespeichert werden dürfen und wann sie gelöscht werden |
| Prüfungsamt | Gibt Regeln für Prüfungstermine vor, etwa Fristen und wer sich anmelden darf |
| Beauftragter für Barrierefreiheit | Verlangt, dass das System auch mit Screenreader und Maus bedienbar ist | 

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Studierende, Lehrende, Sekretariate | Person | Sie arbeiten direkt mit dem Terminplaner und lösen Buchungen und Absagen aus |
| Hochschulkonto der THM | System im Betrieb | Alle melden sich darüber an, also muss der Terminplaner daran angebunden sein | 
| E-Mail-System der THM | System im Betrieb | Buchungsbestätigung | 
| Kalenderprogramme der Nutzer (über iCal) | System im Betrieb | Termine sollen als iCal-Datei in den eigenen Kalender übernommen werden | 
| KI-Agenten | System im Betrieb | Sie sollen über eine API freie Termine abfragen und buchen können | 
| Absage eines Termins wegen Krankheit | Prozess | Das Sekretariat sagt Termine ab und alle Betroffenen müssen informiert werden | 
| Semesterbeginn | Ereignis | Dann legen Lehrende neue Sprechstunden an und es wird besonders viel gebucht | 
| EU-DSGVO | Dokument | Sie regelt, wie mit Namen und Terminen der Studierenden umgegangen werden muss |
| Prüfungsordnung | Dokument | Sie legt Fristen und Regeln für Prüfungstermine fest, an die sich das System halten muss |

## Irrelevante Umgebung

- Speiseplan der Mensa — Er hat nichts mit Sprechstunden oder Prüfungsterminen zu tun
- Ausleihe in der Bibliothek — Bücherausleihe ist ein eigener Vorgang ohne Verbindung zu Terminen mit Lehrenden
