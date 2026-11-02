# Anforderungen — Terminplaner für die THM


| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Das System muss automatisch eine E-mail-Bestätigung an den Studierenden senden, sobald ein Sprechstundentermin erfolgreich gebucht wurde. | Studierende | FA |
| A02 | Lehrende müssen in ihrer Kalenderansicht feste Zeiten blockieren können, in denen keine Termine gebucht werden dürfen. | Lehrende | FA | 
| A03 | Das System muss eine Suchfunktion bereitstellen, mit der Sudierende nach bestimmten Lehrenden oder Fachbereichen suchen können. | Studierende | FA | 
| A04 | Die Ladezeit für das Aufrufen der persönlichen Terminübersicht darf im normalen Betrieb eine Sekunde nicht überschreitern. | Studierende | QA | 
| A05 | Das System muss eine Verfügbarkeit von mindestens 99,5 % während des laufenden Semesterbertriebs aufweisen. | IT-Abteilung | QA | 
| A06 | Das Design der Benutzeroberfläche muss sich automatisch an mobile Endgeräte (Smartphones und Tablets) anpassen. | Studierende | QA | 
| A07 | Der Zugriff auf die Admin-Oberfläche zur Raumverwaltung darf nur aus dem Campus-Netzwerk der THM oder über VPN möglich sein. | IT-Abteilung | RB | 
| A08 | Alle im System gespeicherten Passwörter und Sitzungs-Tokens müssen nach dem aktuellen Stand der Technik verschlüsselt werden. | IT-Abteilung | RB | 
| A09 | Das System darf keine Termine in der Vergangenheit anlegen oder buchen lassen. | Studierende | FA | 


## Eine Anforderung, die niemand ausgesprochen hat


Nummer der Anforderung: **A09**

**Begründung:**


Diese Anforderung wurde im Gespräch von niemandem direkt genannt, da es für alle Beteildigten vollkommen selbstverständlich ist, dass man einen Termin logischerweise nur für die Zukunft vereinbaren kann. Eine Buchungsfunktion für vergangene Tage wäre absolut fehlerhaft und wird daher als implizit vorausgesetzt. 
