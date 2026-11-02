# Anforderungen — Terminplaner für die THM

<!-- Aufgabe 3 des Übungsblatts, ohne Hilfsmittel. Je Zeile eine
     Anforderung in einem Satz, dazu der Stakeholder, von dem sie stammt,
     und die Art: FA, QA oder RB. Mindestens acht Anforderungen, davon
     mindestens zwei je Art; die Nummern laufen A01, A02 … Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Das System muss die gebuchten Termine in einer Kalenderübericht zeigen | Aktive Nutzer: *Lehrende, Schüler & Sekreteriat* | FA |
| A02 | Das System  ermöglicht es eine Terminanfrage zu senden | Schüler | FA |
| A03 | Das System benötigt eine 99% Ausfallsicherheit | Aktive Nutzer: *Lehrende, Schüler & Sekreteriat*  | QA |
| A03 | Das System darf keine Time Slots doppel buchen | Lehrende & Schüler | QA |
| A05 | Das System muss das THM Design (Farbe, Schriftart) haben| Hochschulleitung | RB |
| A06 | Das System muss datenschutzkonform sein | Hochschulleitung, Regierung | RB |
| A07 | Das System ermöglicht den Login mit der THM Mail | Hochschulleitung & aktive Nutzer: *Lehrende, Schüler & Sekreteriat*  | FA |
| A08 | Termine sollen 24h vorher stornierbar sein | Schüler & Lehrende | FA |
| A09 | Das Sekreteriat soll jederzeit Termine stornieren können | QA |


## Eine Anforderung, die niemand ausgesprochen hat

- An Son-& Feiertagen können keine Termine gebucht werden
- Termine sind eindeutigen Nutzern zugewiesen durch eine eineindeutige ID
