# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

* **Studierende:** Nutzen den Terminplaner, um Sprechstunden bei Lehrenden zu buchen.

* **Lehrende:** Bieten die Sprechstunden an und geben ihre verfügbaren Zeiten an.

* **Rechenzentrum der THM:** Verantwortlich für die Bereitstellung des Betriebs der Server-Infrastruktur.

* **Sekretariat:** Pflegt Rahmenbedingungen und Raumpläne im System ein.

* **Datenschutzbeauftragter der THM:** Legt fest, welche personenbezogenen Daten gespeichert, gelöscht und weitergeleitet werden dürfen.

* **Prüfungsamt:** Verantwortlich für die offizielle ANerkennnung von Prüfungsleistungen die auch Beratungsgespräche betreffen.


## Systemkontext


| Aspekt            | Art               | Warum gehört er zum Kontext? |
---------------------------------------------------------------
|E-Mail-Server      |System im Betrieb  |Versendet Bestätigungen und Erinnerungen an Lehrende+Studierende
|Semesterkalender   |Dokument           |Gibt die Vorlesungszeiten vor, in denen die Sprechstunden stattfinden
|Vorlesungsbeginn   |Ereignis           |Löst zu Semesterbeginn eine hohe Anzahl an Terminbuchungen aus.
|Prüfungsordnung    |Dokument           |Regelt Rahmenbedingungen für offiziele Beratung & Prüfungsgespräche
|LDAP-Server der THM|System im Betrieb  |Wir zur Authentifizierung und Anmeldung der Nutzer benötigt.

## Irrelevante Umgebung

* **Kassensystem der Mensa:** Hat keine einzigen Berührungspunkte mit dem Terminplaner.

* **Parkscheinautomat am Campus:** Wir scannen unser Studentenausweis am Gerät, führt uns zur Hochschule, hat auch keine Berphrungspunkte mit dem Terminsplan.