# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Studierende sollen freie Sprechstunden- und Prüfungstermine über eine übersichtliche Ansicht filtern und direkt online buchen können | Studierende | FA |
| A02 | Lehrende müssen ihre verfügbaren Zeitfenster und Kapazitäten für Sprechstunden und Prüfungen eigenständig anlegen, bearbeiten und freigeben können | Lehrende | FA |
| A03 | Die Authentifizierung und Anmeldung am System muss zwingend über das zentrale Hochschulkonto der THM erfolgen | THM | RB |
| A04 | Das System muss die Vorgaben der Datenschutz-Grundverordnung (DSGVO) bei der Speicherung personenbezogener Daten einhalten | Datenschutzbeauftragter | RB |
| A05 | Nach dem Auswählen eines freien Termins muss die Bestätigung der Buchung innerhalb von maximal 1,5 Sekunden auf dem Bildschirm erscheinen | Studierende | QA |
| A06 | Das System muss bei einer gleichzeitigen Nutzung von bis zu 500 aktiven Benutzerinnen und Benutzern stabile Antwortzeiten ohne spürbare Verzögerungen gewährleisten | Rechenzentrum | QA |
| A07 | Sekretariate müssen Vertretungsregeln einrichten können, um Termine im Namen abwesender Lehrender zu verwalten | Sekretariat | FA | 
| A08 | Das System muss verhinder, dass Studierende zwei zeitlich identische Termine bei unterschiedlichen Lehrende zeitgleich buchen können | Studierende | FA |

## Eine Anforderung, die niemand ausgesprochen hat

A08: Diese Anforderung wurde im Gespräch von niemanden geäußert, weil es für alle Beteiligten eine logische Selbstverständlichkeit ist, dass sich eine Person nicht zur selben Zeit an zwei verschiedenen Orten befinden kann. Ein Terminplaner muss daher zeitliche Terminüberschneidungen auf Seiten des Buchenden blockieren. 
