# Anforderungen — Terminplaner für die THM

Kürzel: avon507

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Personbezogene Daten stonierter oder abgelaufener Termine werden nach Ablauf innerhlab von 30 Tagen automatisch gelöscht. | Datenschutzbeauftragter | RB | 
| A02 | Das System sendet automatisch eine Buchungbestätigung per Email an die Studenten. | Studierende | FA | 
| A03 | Termine können 24h vor Terminbeginn stoniert werden. Nach Ablauf der Zeit, gilt die Attestpflicht. | Studierede | FA |
| A04 | Formularfelder enthalten von Screenreadern vorlesbare Beschriftungen und klar erkennbare visuelle Markierungen für beeinträchtigte Studenten. | Studierende | QA | 
| A05 | Neue oder stornierte Termine werden für Lehrpersonen innerhalb von 60 Sekunden im eingebundenen Kalender aktualisiert. | Lehrperson | QA |
| A06 | Die Authentifizierung erfolgt durch den zentralen Identify Provider (CAS) der THM | THM-IT | RB |
| A07 | Das Sekteriat kann Prüfungstermine und Sprechzeiten für alle Lehrpersonen zentral Einsehen und im Vertretungsfall bearbeiten. | Sekteriat | FA|
| A08 | Das System stellt eine API bereit, über die autorisierte KI-Agenten freie Termine abfragen und Buchungen im Auftrag von Nutzenden durchführen können. | IT-THM | FA |

## Eine Anforderung, die niemand ausgesprochen hat

Die Anforderung 01 betrifft gesetzliche Vorgaben zur Löschung personbezogener Daten nach Ablauf von Aufbewahrungsfristen. Die automatische Löschung von Daten nach 30 Tagen ist eine gesetzliche Vorschrift zum Datenschutz. Nutzer verlangen im Gespräch meistens nur Funktionen die sie direkt benutzen (Termine buchen). Dabei werden rechtlich Datenschutzauflagen nur selten von Stakeholdern erwähnt. Das System muss aber diese dringend einhalten. Der Nutzer selbst vergisst dabei oft rechtliche Gesetze im Hintergrund.
…
