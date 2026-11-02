# Anforderungen — Terminplaner für die THM

<!-- Aufgabe 3 des Übungsblatts, ohne Hilfsmittel. Je Zeile eine
     Anforderung in einem Satz, dazu der Stakeholder, von dem sie stammt,
     und die Art: FA, QA oder RB. Mindestens acht Anforderungen, davon
     mindestens zwei je Art; die Nummern laufen A01, A02 … Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Lehrende können neue Sprechstundentermine mit Datum, Uhrzeit und Ort anlegen. | Lehrende | FA |
| A02 | Studierende können eine Terminbuchung bis zu 24 Stunden vor dem Termin stornieren. | Studierende | FA |
| A03 | Das System sendet unmittelbar nach erfolgreicher Buchung eine Bestätigung per E-Mail an Studierende und Lehrende. | Studierende / Lehrende | FA |
| A04 | Lehrende können eine Notiz zu einem absolvierten Termin im System hinterlegen. | Lehrende | FA |
| A05 | Die Benutzeroberfläche muss auf mobilen Endgeräten (Smartphones) ohne Einschränkungen nutzbar sein. | Studierende | QA |
| A06 | Das Suchen nach verfügbaren Terminen einer bestimmten Lehrperson darf nicht länger als 1 Sekunde dauern. | Studierende | QA |
| A=7 | Die Authentifizierung aller Benutzer muss über das zentrale Single-Sign-On (SSO) der THM erfolgen. | IT-Abt. / THM | RB |
| A08 | Alle gespeicherten Daten müssen auf Servern innerhalb der Europäischen Union gehostet werden. | Datenschutzbeauftragte | RB |
| A09 | Ein Terminslot darf zu keinem Zeitpunkt von zwei verschiedenen Personen gleichzeitig gebucht werden. | Studierende / Lehrende | FA |

## Eine Anforderung, die niemand ausgesprochen hat

<!-- Nummer der Anforderung aus der Tabelle, welche im Gespräch niemand
     ausgesprochen hat, obwohl sie gilt, und in ein bis zwei Sätzen, warum
     sie niemand genannt hat. -->

- **Anforderung:** Ein Terminslot darf zu keinem Zeitpunkt von zwei verschiedenen Personen gleichzeitig gebucht werden.
- **Begründung:** Diese Anforderung wurde im Gespräch von niemandem genannt, da es für alle Beteiligten vollkommen selbstverständlich ist und dem Grundprinzip einer Terminvergabe widerspricht, dass ein bereits belegter Slot doppelt vergeben werden kann.
