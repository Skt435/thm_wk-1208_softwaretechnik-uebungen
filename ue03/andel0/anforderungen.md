# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Die THM benötigt eine Software zur Planung und Vereinbarung von Terminen. | THM | FA |
| A02 | Studierende sollen in der Lage zu sein Sprechtstunden bei Lehrenden zu buchen. | Lehrende/Studierende | FA |
| A03 | Der Terminplaner soll bei starken Lasten, wenn bpsw. 2000 Studierende zur selben Zeit einen Termin buchen, nicht länger als 2 Sekunden benötigen, um zu reagieren. | Studierende | QA |
| A04 | Studierende sollen den Buchungsvorgang in weniger als 3 Schritten absolvieren können. | Studierende | QA |
| A05 | Die Datenverarbeitung muss den Regelungen der EU-DSGVO folgen. | IT-Abteilung | RB |
| A06 | Der Terminplaner soll nicht extern sondern, im Rechenzentrum der THM laufen. | IT-Abteilung | RB |
| A07 | Sobald ein Dozent einen Termin absagt, bekommen alle Studierende, die den jeweiligen Termin gebucht haben, eine Benachrichtigung. | Lehrende | FA |
| A08 | Eine bereits erfolgreich getätigte Terminbuchung darf im System für andere Nutzer nicht mehr als frei verfügbar angezeigt werden. | Studierende | QA |

## Eine Anforderung, die niemand ausgesprochen hat

| Nr. | Anforderung | Stakeholder| Art |
|---|---|---|---|
| A09 | Endnutzer dürfen nicht in der Lage sein, einem befristeten Termin nach Ablauf weiterhin zu buchen. | IT-Sicherheitsbeauftragter | RB | 

> BEGRÜNDUNG-A09: Ich denke, dass so etwas niemand erwähnen würde, da so etwas ein Designfehler wäre und auch eventuell selbstverständlich für eine Hochschule ist, die einen Terminplaner benötigt. Falls so etwas jedoch nicht implementiert wird, dann wäre das System manipulierbar, wenn bspw. ein Studierender sich nach der Anmeldefrist für eine Klausur immernoch bewerben kann.