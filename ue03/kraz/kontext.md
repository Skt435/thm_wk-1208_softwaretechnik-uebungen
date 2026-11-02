# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Lehrende | Sie bieten Sprechstunden und Prüfungstermine an und bestimmen, wie das Anbieten von Terminen ablaufen soll. |
| Studierende | Sie buchen die Termine, deshalb hängt von ihnen ab, wie einfach und schnell das Buchen sein muss. |
| Sekretariate | Sie brauchen den Überblick über alle Termine ihres Fachbereichs und bestimmen, welche Übersichten es geben muss. |
| Hochschulleitung der THM (Auftraggeber) | Sie bezahlt das Projekt und entscheidet über Budget, Zeitplan und Umfang. |
| Rechenzentrum der THM | Es betreibt das System später und gibt vor, welche Technik und welches Hochschulkonto-Login genutzt werden. |
| Datenschutzbeauftragte der THM | Sie achtet darauf, dass Namen und Termindaten nur so gespeichert werden, wie es die DSGVO erlaubt. |
| Prüfungsamt | Es legt fest, welche Regeln für Prüfungstermine gelten, z.B. wer sie absagen darf. |
| Schwerbehindertenvertretung | Sie sorgt dafür, dass das System barrierefrei bedienbar ist, z.B. mit einem Screenreader. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Studierende, Lehrende und Sekretariate | Person | Sie bedienen das System direkt, sind aber selbst nicht Teil davon. |
| KI-Agent | System im Betrieb | Er greift von außen über die API auf das System zu und bucht im Namen einer Person. |
| Hochschulkonto (Login der THM) | System im Betrieb | Der Terminplaner muss die Anmeldung darüber abwickeln, baut das Login aber nicht selbst. |
| Kalenderprogramme der Beteiligten (z.B. Outlook) | System im Betrieb | Sie müssen die iCal-Dateien lesen können, die der Terminplaner erzeugt. |
| Prüfungsanmeldung | Prozess | Zu Beginn der Prüfungsanmeldung buchen sehr viele Personen gleichzeitig, darauf muss das System vorbereitet sein. |
| Semesterbeginn | Ereignis | Zu Semesterbeginn legen viele Lehrende gleichzeitig neue Sprechstunden an. |
| Prüfungsordnung | Dokument | Sie gibt Regeln für Prüfungstermine vor, an die sich das System halten muss. |
| EU-DSGVO | Dokument | Sie regelt, wie mit personenbezogenen Daten umgegangen werden muss. |

## Irrelevante Umgebung

- Mensa und Speiseplan — haben mit Terminen in Sprechstunden oder Prüfungen nichts zu tun.
- Parkplätze auf dem Campus — wer wo parkt, spielt für das Buchen eines Termins keine Rolle.
