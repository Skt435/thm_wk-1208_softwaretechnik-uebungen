# Stakeholder und Systemkontext — Terminplaner für die THM

<!-- Aufgabe 1 des Übungsblatts. Ersetzen Sie die Platzhalter … und fügen
     Sie so viele Zeilen hinzu, wie Sie benötigen. Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

## Stakeholder
| Stakeholder | Einfluss auf die Anforderungen |
| :--- | :--- |
| *Lehrende* | Sie beeinflussen die Anforderungen bezüglich der flexiblen Bereitstellung, Verwaltung und Absage von Sprechstunden- und Prüfungsterminen. |
| *Studierende* | Sie stellen Anforderungen an das unkomplizierte Suchen, Buchen und Einsehen von freien Terminen über ihre Hochschulkonten. |
| *Sekretariate* | Sie beeinflussen die Anforderungen bezüglich einer zentralen Übersicht aller Termine und der administrativen Verwaltung für die Lehrenden. |
| *Rechenzentrum / IT-Betrieb der THM* | Es stellt Anforderungen an den sicheren Betrieb, die Bereitstellung der Serverinfrastruktur sowie die Anbindung an die THM-Hochschulkonten. |
| *Entwicklerteam (eigene Firma)* | Wir nehmen Einfluss auf die technische Architektur, die Integration der API-Schnittstelle sowie die Umsetzbarkeit für KI-Agenten. |
| *Datenschutzbeauftragter der THM* | Er bestimmt die Anforderungen an die DSGVO-konforme Verarbeitung personenbezogener Daten bei der Terminbuchung. |


| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| … | … |

## Systemkontext


| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| | *Hochschulkonto / SSO-Authentifizierung der THM* | System im Betrieb | Das System muss mit der bestehenden Benutzerverwaltung der THM umgehen können, damit sich Studierende, Lehrende und Sekretariate mit ihren bestehenden THM-Konten anmelden. |
| *Kalender-Software der Beteiligten (z. B. Outlook, Apple Calendar)* | System im Betrieb | Das System muss iCal-Dateien bereitstellen und in einer späteren Ausbaustufe eine direkte Schnittstelle zur Synchronisation mit externen Kalendern bieten. |
| *KI-Agenten* | System im Betrieb | Das System muss eine Programmierschnittstelle (API) bereitstellen, über die externe KI-Agenten Buchungsprozesse und Terminabfragen steuern können. |
| *Bisherige Buchungswerkzeuge (DFN-Terminplaner, Doodle, Listen an der Bürotür)* | Prozess | Das neue System muss die bisherigen manuellen und dezentralen Abläufe vollständig ablösen und berücksichtigen, wie Termine bisher vereinbart wurden. |
| *E-Mail-Infrastruktur der THM* | System im Betrieb | Das System muss automatische E-Mail-Benachrichtigungen und Bestätigungen bei Terminbuchungen oder -änderungen versenden. |

## Irrelevante Umgebung


- *Mensa-Kassensystem der THM*  Die Abrechnung von Speisen steht in keinerlei funktioneller oder technischer Verbindung zur Vereinbarung von Prüfungs- und Sprechstundenterminen. 
- *Bibliotheksverwaltung (Ausleihe und Katalog / OPAC)*  Das Ausleihen von Medien ist ein eigenständiger Prozess, der für die Buchung von Beratungsterminen bei Lehrenden keine Rolle spielt. 
