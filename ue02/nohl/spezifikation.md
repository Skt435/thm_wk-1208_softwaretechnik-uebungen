# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @nilsowen

## Derzeitiger Zustand und Wünsche für die Zukunft

Termine werden heute vereinbart über:

- E-Mail
- Listen an der Bürotür
- Werkzeuge im Netz, nämlich
    - [DFN-Terminplaner](https://terminplaner6.dfn.de/de)
    - [Doodle](https://doodle.com/de/)

Die THM will vermeiden, dass es wieder ein neues Werkzeug gibt, das am Ende niemand benutzt.

## Anforderungen der Endanwender

| Wer | Was |
|---|---|
| Professoren | tragen Klausuren, Vorlesungs- und Übungstermine ein |
| Studierende | buchen Sprechstunden und Lehrveranstaltungen |
| Sekretariate | haben den Überblick über alle Termine |
| KI-Agenten | steuern das System über eine Schnittstelle (API) |

## Technische Anforderungen an das System

- Bedienung über das Hochschulkonto
- Termine als iCal-Datei zum Herunterladen
- später vielleicht direkt in die Kalender der Beteiligten eintragen