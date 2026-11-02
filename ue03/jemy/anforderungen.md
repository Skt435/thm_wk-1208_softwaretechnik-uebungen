# Anforderungen — Terminplaner für die THM

<!-- Aufgabe 3 des Übungsblatts, ohne Hilfsmittel. Je Zeile eine
     Anforderung in einem Satz, dazu der Stakeholder, von dem sie stammt,
     und die Art: FA, QA oder RB. Mindestens acht Anforderungen, davon
     mindestens zwei je Art; die Nummern laufen A01, A02 … Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Lehrende müssen die Möglichkeit haben, Termine verwalten und anbieten zu können | Lehrende | FA |
| A02 | Studierende müssen die Möglichkeit haben Termien zu stornieren | Studierende | FA |
| A03 | Der Terminplaner (die UI) soll Studieren ermöglichen in wenigen Schritten Termine zu buchen | Studierende | QA |
| A04 | Der Terminplaner soll für die 14.443 Studierende weiterhin performant sein | Studierende | QA |
| A05 | Die Authentifizierung der Studierenden muss über das bestehende Hochschulkonto der THM erfolgen | THM-IT | RB |
| A06 | Personenbezogene Daten müssen gemäß den Vorgaben der EU-DSGVO verarbeitet werden | Hochschule | RB |
| A07 | Das System muss eine Verfügbarkeit von mindestens 99,5 % während der Vorlesungszeit gewährleisten | THM-IT | QA |
| A08 | Es muss ein Berechtigungskonstrukt vorhanden sein, wer was darf, wer was sehen kann etc. | Hochschule | RB |
## Eine Anforderung, die niemand ausgesprochen hat

<!-- Nummer der Anforderung aus der Tabelle, welche im Gespräch niemand
     ausgesprochen hat, obwohl sie gilt, und in ein bis zwei Sätzen, warum
     sie niemand genannt hat. -->

****Ein bereits belegter Termin kann nicht erneut gebucht werden.****

Diese Anforderung wurde im Gespräch nicht genannt, da davon ausgegangen wird, dass ein Terminplaner Doppelbuchungen verhindert. Ohne diese Funktion könnten mehrere Studierende denselben Termin buchen, wodurch Konflikte entstehen würden.
