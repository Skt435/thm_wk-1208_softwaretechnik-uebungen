# Stakeholder und Systemkontext — Terminplaner für die THM

---

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| **Studierende** | Wollen schnell freie Termine finden, buchen und Bestätigungen erhalten. |
| **Lehrende (Dozenten/Professoren)** | Bestimmen, wie Zeitfenster angelegt werden und wie Termine vergeben werden. |
| **Sekretariat** | Benötigt den Gesamtüberblick über Raum- und Terminplanungen bei Konflikten. |
| **DV-Zentrum (IT-Abteilung)** | Gibt die Sicherheits- und Login-Standards (SSO/LDAP) für den Betrieb vor. |
| **Datenschutzbeauftragte** | Bestimmt, welche Personen Daten sehen dürfen und wann alte Daten gelöscht werden müssen. |
| **Fachbereichsleitung / Dekanat** | Legt Rahmenbedingungen für Raumkapazitäten und Sprechstundenzeiten fest. |

---

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| **THM-Login-System (SSO)** | System im Betrieb | Der Terminplaner nutzt die THM-Zugangsdaten zur Anmeldung, läuft aber als eigene Anwendung separat davon. |
| **Mailserver der THM** | System im Betrieb | Das System sendet darüber automatisierte Buchungsbestätigungen und Erinnerungen an Studierende und Lehrende. |
| **Semester- und Vorlesungsplan** | Dokument | Gibt vor, an welchen Tagen überhaupt Sprechstunden sinnvoll angeboten werden können. |
| **Prüfungsanmeldephase** | Ereignis | Führt kurzfristig zu sehr vielen gleichzeitigen Zugriffs- und Buchungsanfragen auf den Terminplaner. |
| **Prüfungsordnung der THM** | Dokument | Legt fest, welche Fristen bei der Vereinbarung von Prüfungsterminen rechtlich eingehalten werden müssen. |

---

## Irrelevante Umgebung

- **Mensa-Speiseplan** — Das Speisenangebot an der THM hat keinen Einfluss darauf, wie Termine gebucht oder verwaltet werden.
- **Bibliotheks-Katalog (OPAC)** — Die Ausleihe von Büchern läuft unabhängig ab und benötigt keine Schnittstelle zur Terminvergabe von Dozenten.