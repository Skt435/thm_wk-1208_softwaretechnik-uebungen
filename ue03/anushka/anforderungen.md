# Anforderungen – Terminplaner für die THM

---

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Studierende müssen verfügbare Sprechstundentermine bei Lehrenden suchen und verbindlich buchen können. | Studierende | FA |
| A02 | Lehrende können verfügbare Zeitfenster für Sprechzeiten eigenständig im Kalender erstellen. | Lehrende | FA |
| A03 | Das System verschickt nach der Buchung automatisch eine Bestätigung per E-Mail an beide Partner. | Studierende | FA |
| A04 | Das Sekretariat erhält Rechte, um Terminüberschneidungen manuell im System anzupassen. | Sekretariat | FA |
| A05 | Die Webanwendung muss für die Nutzung auf mobilen Endgeräten wie Smartphones optimiert sein. | Studierende | QA |
| A06 | Die Ladezeit bei der Abfrage von freien Zeitslots darf maximal 3 Sekunden betragen. | Lehrende | QA |
| A07 | Der Login muss zwingend über den zentralen THM-Single-Sign-On-Dienst erfolgen. | DV-Zentrum | RB |
| A08 | Die Speicherung aller personenbezogenen Buchungsdaten muss konform mit der DSGVO erfolgen. | Datenschutzbeauftragte | RB |

---

## Eine Anforderung, die niemand ausgesprochen hat

**A01 (Ausschluss von Mehrfachbuchungen)**

Niemand hat diesen Punkt im Gespräch erwähnt, da ein automatischer Doppelbuchungsschutz bei einem digitalen Terminkalender von allen als implizite Grundfunktion vorausgesetzt wird.
