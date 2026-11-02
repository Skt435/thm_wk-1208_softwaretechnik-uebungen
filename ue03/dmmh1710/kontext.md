# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Schüler |Wollen schnell freie termine finden|
|Lehrende|Bestimmen das Zeitfenster und wie Termine Vergeben werden|
|Prüfungsamt|Gibt rechtliche Vorgaben und Fristen bezüglich prüfungsrelevanten Beratunsgterminen|
|Personalrat|Legt Vorgaben fest dass das System nicht zur Verhaltens oder Leistungskontrolle von Lehrenden und Mitarbeitenden genutzt werden darf|
|Dekanat/Fachbereichsleistung|Entscheidet über die Bereitstellung von Ressourcen und Terminabwicklung|
|Software Enteicklung|Beeinflusst die die teschniche Architektur, den Code Standard und die Wartbarkeit der Anwendung|

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
|Studierende/Lehrende |Person| Nutzt das System direkt, um Termine zu suchen, anzubieten, zu Buchen oder abzusagen|
|Thm Single Sign-On|System im Betrieb|Stellt die zentrale Authentifizierung bereit, damit sich Nutzer mit ihren THM Zugangsdaten einloggen können|
|THM E-Mail_Server|System im Betrieb|Übernimmt den automatisierten Versand von Buchungsbestätigungen, Erinnerungen und absagen|
|Sprechstundenbuchung|Prozess|Beschreibt den Ablauf von der Terminauswahl über die Validierung von Zeitfenstern bis zur Bestätigung|
|Terminstornierung|Ereignis|Löst automatisierte Benachrichtigungen aus  und gibt gebuchte Zeitslots sofort wieder für andere frei|

## Irrelevante Umgebung

- **Mensa-Kassensystem / Speiseplan** — Verwaltet die Gastronomie und Zahlung des Studierendenwerks und hat keinerlei Berührungspunkte mit der Buchung von akademischen Sprechstunden.
- **Bibliotheks-Ausleihesystem (OPAC)** — Ist rein für die Erfassung und Recherche von Literatur sowie Buchausleihen zuständig und agiert völlig unabhängig vom Terminplaner.
