# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Lehrende | Welche Sprechstunden und Prüfungstermine angeboten werden und wie sich das Anlegen und Verwalten von Terminen anfühlen muss. |
| Studierende | Wie das Suchen, Buchen und Stornieren von Terminen abläuft und ob das System überhaupt angenommen wird. |
| Sekretariate | Welche Übersichten über Termine und Buchungen ihres Bereichs nötig sind. |
| Hochschulleitung (Auftraggeber) | Budget, Umfang und Zeitplan des Projekts sowie die grundsätzlichen Entscheidungen. |
| Rechenzentrum der THM | Betrieb, Systembasis und die Anbindung an das Hochschulkonto. |
| Datenschutzbeauftragte der THM | Welche personenbezogenen Daten gespeichert, wie lange sie aufbewahrt und wer sie sehen darf. |
| Prüfungsamt | Welche Regeln für Prüfungstermine gelten, z.B. Fristen und Anmeldung zur Prüfung. |
| Personalrat | Ob das System Rückschlüsse auf Arbeitszeit oder Verhalten der Beschäftigten zulässt. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Lehrende, Studierende, Sekretariate | Person | Sie bedienen das System direkt und bestimmen, welche Funktionen es braucht. |
| Anmeldung über das Hochschulkonto | System im Betrieb | Der Terminplaner muss sich an die bestehende Anmeldung anbinden und deren Benutzer und Rechte übernehmen. |
| KI-Agenten über die API | System im Betrieb | Sie steuern das System von außen und brauchen klar festgelegte Vorgänge und Rechte. |
| Kalenderprogramme der Beteiligten (iCal-Import) | System im Betrieb | Die heruntergeladenen iCal-Dateien müssen sich dort öffnen lassen. |
| Sprechstunde vereinbaren und durchführen | Prozess | Das ist der Kernablauf, den das System unterstützen soll. |
| Prüfungsanmeldung und Prüfungszeitraum | Prozess / Ereignis | Prüfungstermine müssen zu den Fristen und Zeiträumen der Prüfungsorganisation passen. |
| Semesterbeginn und Vorlesungszeit | Ereignis | Zu diesen Zeitpunkten werden Sprechstunden neu angelegt, und die Last auf dem System steigt. |
| Prüfungsordnung und Datenschutzvorgaben (DSGVO) | Dokument | Sie legen Regeln fest, die das System einhalten muss. |

## Irrelevante Umgebung

- Mensa und ihr Bezahlsystem — mit der Vereinbarung von Terminen haben sie nichts zu tun.
- Bibliotheksausleihe — sie läuft über ein eigenes System und berührt weder Sprechstunden noch Prüfungstermine.