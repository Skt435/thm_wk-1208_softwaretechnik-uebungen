# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder


| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Studierende | Sie bestimmen die Anforderungen an die mobile Nutzung, Benachrichtigungen und einfache Buchung von Terminen. |
| Lehrende / Professoren | Sie beeinflussen die Funktionen zur Verwaltung von Sprechstunden, Terminblockaden und die Synchronisation mit eigenen Kalendern. | 
| IT-Abteilung / Admins der THM | Sie bestimmen die technischen Rahmenbedingungen für den Betrieb, Schnittstellen und Serverkapazitäten. | 
| Prüfungsamt | Sie nehmen Einfluss auf Sperrzeiten im Kalender, damit Termine nicht mit zentralen Klausuren kollidieren. | 
| Fachbereichssekretariate | Sie beinflussen die Raum- und Ressourcenplanung, da Sprechstunden oft an bestimmte Räume gebunden sind. | 
| Datenschutzbeauftragte der THM | Sie redet bei den Sicherheitsanforderungen mit, damit keine privaten Buchungsdaten unbefugt eingesehn werden können. | 


## Systemkontext


| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Moodle | System im Betrieb | Der Terminplaner muss Fristen oder Kurstermine mit Moodle austauschen können. |
| THM-Identity-Management (Login-Server) | System im Betrieb | Nutzer müssen sich mit ihren bestehenden THM-Zugangsdaten am System authentifizieren. | 
| Hessisches Datenschutzgesetzt (HDSIG) / DSGVO | Dokument | Es gibt rechtlich bindende Regeln vor, wie Nutzerdaten im System automatisch verarbeiten muss. | 
| Semesterstart | Ereignis | Zu diesem Zeitpunkt ändert sich der gesamte Grund-Stundenplan, was das System automatisch verarbeiten muss. | 
| Prüfungsanmeldung | Prozess | Dieser organisatorische Ablauf bestimmt die Phasen, in denen der Terminplaner besonders hoch ausgelastet ist. | 

## Irrelevante Umgebung


| Ding | Warum spielt es keine Rolle? | 
|---|---| 
| THM-Mensa-Speiseplan | Das Essensangebot hat keinerlei logischen oder datentechnischen Bezug zur akademischen Termin- und Sprechstundenplanung. | 
| Parkplatz-ZUfahrtsschranke der THM | Dies ist ein rein physisches Zugangssystem, das völlig unabhängig von Vorlesungs- oder Beratungsterminen operiert. | 