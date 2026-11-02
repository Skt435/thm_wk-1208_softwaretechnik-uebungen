# Stakeholder und Systemkontext – Terminplaner für die THM

---

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| **Studierende** | Suchen passende Termine, buchen diese direkt und erwarten Bestätigungen sowie Erinnerungen. |
| **Lehrende (Dozenten/Professoren)** | Tragen ihre freien Zeitfenster ein und legen fest, nach welchen Regeln Slots vergeben werden. |
| **Sekretariat** | Braucht Übersicht über die Belegung von Räumen und Terminen, um Überschneidungen zu klären. |
| **DV-Zentrum (IT-Abteilung)** | Gibt die Richtlinien für die Authentifizierung (SSO/LDAP) und den sicheren Serverbetrieb vor. |
| **Datenschutzbeauftragte** | Legt fest, wer Zugriff auf Buchungsdaten hat und wann diese automatisch gelöscht werden müssen. |
| **Fachbereichsleitung / Dekanat** | Gibt organisatorische Rahmenbedingungen bezüglich Raumkapazitäten und Sprechzeiten vor. |

---

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| **THM-Login-System (SSO)** | Externe Schnittstelle | Liefert die Nutzerdaten zur Anmeldung, wird vom Terminplaner aber nur als externer Dienst angefragt. |
| **Mailserver der THM** | Externe Schnittstelle | Übernimmt den automatischen Versand von Buchungsbestätigungen und Erinnerungsmails. |
| **Semester- und Vorlesungsplan** | Vorgabe / Dokument | Zeigt auf, in welchen Zeitfenstern Sprechstunden überhaupt sinnvoll eingeplant werden können. |
| **Prüfungsanmeldephase** | Ereignis | Sorgt zeitweise für sehr hohe Serverlast durch viele zeitgleiche Buchungsversuche. |
| **Prüfungsordnung der THM** | Regelwerk | Entält die rechtlich bindenden Fristen, die bei Terminabsprachen eingehalten werden müssen. |

---

## Irrelevante Umgebung

- **Mensa-Speiseplan** – Die Essensauswahl hat keinerlei Auswirkung auf die Buchung oder Verwaltung von Terminen.
- **Bibliotheks-Katalog (OPAC)** – Literaturrecherchen und Buchausleihen laufen separat und brauchen keine Verbindung zur Terminvergabe.
