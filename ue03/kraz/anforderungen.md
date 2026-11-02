# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Lehrende können eine Sprechstunde mit festen Zeitfenstern anlegen, z.B. jeden Dienstag 10–12 Uhr in 15-Minuten-Slots. | Lehrende | FA |
| A02 | Studierende können einen gebuchten Termin selbst wieder absagen, danach ist der Slot wieder frei. | Studierende | FA |
| A03 | Das Sekretariat kann Prüfungstermine für die Lehrenden seines Fachbereichs anlegen und ändern. | Sekretariate | FA |
| A04 | Nach einer Buchung bekommen Studierende eine Bestätigung per E-Mail. | Studierende | FA |
| A05 | Ein Termin kann nicht in der Vergangenheit angelegt oder gebucht werden. | Lehrende, Studierende | FA |
| A06 | Eine Lehrperson kann eine neue Sprechstunde in weniger als zwei Minuten anlegen. | Lehrende | QA |
| A07 | Das System ist während der Vorlesungszeit zu mindestens 99 % der Zeit erreichbar. | Rechenzentrum der THM | QA |
| A08 | Die Buchung funktioniert auch auf dem Handy, ohne dass man seitlich scrollen muss. | Studierende | QA |
| A09 | In der ersten Ausbaustufe gibt es nur den iCal-Download, die direkte Eintragung in Kalender kommt erst später. | Hochschulleitung der THM | RB |
| A10 | Gebuchte Termine von Studierenden werden spätestens ein Jahr nach dem Termin gelöscht. | Datenschutzbeauftragte der THM | RB |
| A11 | Prüfungstermine dürfen nur so abgesagt oder verschoben werden, wie es die Prüfungsordnung erlaubt. | Prüfungsamt | RB |

## Eine Anforderung, die niemand ausgesprochen hat

A05: Dass man keinen Termin in der Vergangenheit buchen kann, ist für alle so selbstverständlich, dass im Gespräch niemand daran gedacht hat. Wenn es aber nicht in der Spezifikation steht, könnte das Entwicklerteam es vergessen.
