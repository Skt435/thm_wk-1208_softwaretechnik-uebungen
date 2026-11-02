# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Entwickler | Hat Einfluss auf die Umsetzung und Erreichung des Ziels ebenfalls auf die spätere Wartung. |
| THM | Kunde welcher angibt welche Anforderungen an das System gelten. |
| Lehrende | Haben Einfluss darauf, wie die ansicht der Terminerstellung sein sollen und bieten Termine an. |
| Studierende | Es muss einen Interface geben wo Studierende ihre Termine anzeigen lassen können und man muss bei der Erstellung der Anwendung darauf achten, dass diese selbstverständlich sind. Die Suche nach freien Terminen wird beeinflusst und die Buchung und Widerrufung von Terminen. |
| Sekreteriate | Haben Einfluss auf die Verwaltung der Termine und Organisation der Termine, damit es zeitlich gut passt mit den Vorlesungen der Studierenden. |
| Datenschutzbeauftrage | Haben Einfluss auf die Handhabung der Informationen der Studierenden, Lehrende und der Sekreteriate, damit es datenschutzkonform ist und man keinen Schwierigkeiten mit der Datenschutzbehörde hat. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| THM Webmail | Ereignis | Der Terminplaner versendet kurz vor Terminstart eine Email via Webmail um den Student zu erinnern. |
| idp bzw Personenauthentifikation | System in Betrieb | Um den Terminplaner zu nutzen muss man sich zuvor anmelden und authentifizieren, ob man wirklich student ist und um seine Termine einsehen zu können. |
| Moodle | System in Betrieb | Um Termine zu Buchen soll geprüft werden bei welchen Professoren man in moodle eingeschrieben ist, um dann nur deren Termine zu buchen und nicht die eines Professoren den man nie haben wird. |
| Studierende | Person | Studierende nutzen den Terminplaner damit sie freie Termine finden und diese dann buchen und widerrufen können. Dies muss so angepasst werden, damit es so intuitiv wie möglich ausfällt und jeder den Planer nutzen kann. |
| Professoren | Person | Bieten Termine an und müssen diese später auch Verwalten können. |
| Aufall und Verschiebung eines Termins | Ereignis | Wenn ein Termin ausfällt und der zugehörige Professor einen Ersatztermin anlegt soll automatisch der zugehörige Student mit seinen daten übernommen werden, sodass der Student nicht einen neuen Termin suchen muss. Zusätzlich kann die Person via Webmail informiert werden, dass ein neuer Termin ansteht und der alte ausfällt. |

## Irrelevante Umgebung

- Moodle Ansprechpersonen — Die Ansprechpersonen sind da wenn man mit Moodle nicht gut umgehen kann und noch offene Fragen hat. Dies spielt für den Terminplaner keine Rolle, weil diese Ansprechpersonen den Terminplaner nicht erklären und mit was anderem beschäftigt sind.
- THM Bibliothek — Der Terminplaner hat mit der Hochschulbibliothek an sich nichts zutun, da diese nur für Verleih und Rückgabe der Bücher zuständig sind und nicht an die Vergabe der Termine teilhaben. 
- THM Parkplätze - Die Parkplätze der THM haben mit dem Terminplaner nichts zutun.
