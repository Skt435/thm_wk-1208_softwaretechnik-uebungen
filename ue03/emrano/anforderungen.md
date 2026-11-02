# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Professor legt einen Termin an bzw kann Termine erstellen und verwalten. | Professor | FA |
| A02 | Termine sollen sich nicht mit Vorlesungen überschneiden, weil Studierende sonst eine Vorlesung verpassen und alles nachholen müssten. | Studierende | FA |
| A03 | Termine sollen übersichtlich angezeigt werden, damit man als Student nur seine eigenen Termine einsehen kann und schneller und übersichtlicher sieht wann der nächste Termin stattfindet. | Studierende | QA |
| A04 | Das Interface, womit Professoren ihre Termine anlegen und Verwalten, soll nicht komplex sein und schnelle Erstellung sowie Verwaltung zulassen, damit Professoren nicht zu oft rumklicken müssen um ein Termin zu erstellen. Es soll außerdem intuitiv aufgebaut sein damit es viel schneller und einfacher geht. | Professoren | QA |
| A05 | Das System wird regelmäßig gewartet, damit die aktuellsten Sicherheitslücken und gesetzlichen Richtlinien wie z.b. die DSGVO-Richtlinien eingehalten werden, damit die Software einwandfrei funktioniert und es keine Bußgelder gibt. | Entwickler und THM | RB |
| A06 | Die Entwicklungskosten dürfen nicht mehr als 20.000€ sein und die Entwicklung soll bis zu 2 Jahre andauern, damit das Budget der THM nicht zu sehr ausgeschöpft wird und damit man ein Ergebnis schnell zur Verfügung hat. | Entwickler und THM | RB |
| A07 | Kurz vor dem Termin wird eine Email mit den Daten zum Termin an den Studierenden geschickt, damit diese erinnert wird und zusätzliche Informationen wie den Raum und Uhrzeit schneller findet. | Studierende | FA |
| A08 | Termine werden direkt in die Kalender der Beteiligten eingetragen und übermittelt. | Studierende und Professoren | FA |
| A09 | Erreichbarkeit der Webseite oder der App des Terminplaners sollte Dauerhaft oder so hoch wie möglich sein, damit man fast keine Ausfälle hat. | Studierende, Professoren und das Sekreteriat | QA |
| A10 | Sonntags darf es keine Termine geben, weil es ein Ruhetag ist und da keiner Arbeiten soll bzw ein Termin anbieten soll. Diese Tage sollen gesperrt werden und nicht zur Verfügung stehen bei der Terminerstellung | Studierende und Professoren | FA |

## Eine Anforderung, die niemand ausgesprochen hat

- A09 - Die dauerhafte Erreichbarkeit des Planers hat im Gespräch niemand genannt, weil Erreichbarkeit für viele eine Vorraussetzung ist die man nicht sehr wahrnimmt, bis man die Webseite nicht mehr erreicht. Deshalb sollte die Erreichbarkeit wichtig sein und eine Anforderung auf die man achten soll, damit es keine Probleme mit der Einsicht in Termine gibt, während die Webseite nicht erreichbar ist. 
- A10 - Ebenso wurde im Gespräch vergessen zu sagen, dass man sonntags keine Termine anbieten darf, weil das ein Ruhetag ist und man muss funktional alle Sonntage bei der Terminerstellung sperren. Daran wurde im Gespräch nicht gedacht, weil man es für selbstverständlich findet, dass man am Sonntag Zuhause ist und nicht arbeitet und deshalb wurde es übersehen, weil es selbstverständlich ist.
