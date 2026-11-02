# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Hochschule | Liefert Budget und Anforderungen |
| Studenten | Anforderungen (Benutzeroberfläche aus der Sicht des Buchers von Kursen) |
| Dozenten | Anforderungen (Benutzeroberfläche aus der Sicht des Anbieters von Kursen) |
| Sekretariat | Anforderungen und Anpsrechpartner für Rückfragen (Will eine Übersicht über alles haben. Zusätzliche Admin-Oberfläche) |
| Hochschule-IT | Liefert die Schnittstelle für das Log-In über das Hochschulkonto |
| Anbieter für KI-Agenten | Anforderungen an die API |
| Entwicklerteam der Hochschule | Braucht eine gute Spezifikation um dann damit arbeiten zu können mit möglichst wenig Rückfragen. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Hochschul-Login | System im Betrieb | Das Tools soll mit einem Account der Hochschule bedient werden |
| Moodle | System im Betrieb / Prozess | Begleitend zu den Terminen steht im Zweifel zusätzliche Information und Material zum Termin in Moodle. |
| Dozent | Person | Stellt die Termine für Studenten |
| Terminablauf | Prozess | Wie die Termine strukturiert sind passiert auserhalb des Planers. Dozent und Sekretariat stimmen sich ab. |
| Student | Person | Hauptnutzer vom System. |

## Irrelevante Umgebung

- Mensa — Auch wenn diese Öffnungszeiten hat, sind diese keine klassichen Termine im Sinne des Terminplaners
- Bücher — Die Bibliothek kann Termine anbieten und auch Räume anbieten. Aber welche Bücher aktuell sind in der Bibliothek befinden sind nicht relevant für den Terminplaner. Dafür ist das Tool der Bibliothek zuständig.
