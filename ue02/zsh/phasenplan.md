# Phasenplan — Terminplaner für die THM

Kürzel: zsh

## Studie

**Ergebnis der Phase:** Machbarkeitsstudie

- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen

## Systemspezifikation

**Ergebnis der Phase:** Lastenheft

- Die Komponente „Benachrichtigung“ programmieren
- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen
- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden

## Systemkonstruktion

**Ergebnis der Phase:** Architekturenentwurf

- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Datenbank, Programmiersprache und Web-Framework auswählen

## Implementierung

**Ergebnis der Phase:** Quellcode

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen

## Integration & Einführung

**Ergebnis der Phase:** Betriebsbereites System

- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Aufwand schätzen und einen Meilensteinplan vorschlagen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt

## Wartung

**Ergebnis der Phase:** Gewartetes System

- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung** (Implementierung): …
- **Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen** (Systemkonstruktion): …
- **Datenbank, Programmiersprache und Web-Framework auswählen** (Systemkonstruktion): …
- **Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen** (Implementierung): …

<!-- zuordnung ue02-phasenplan: k01=spezifikation k02=spezifikation k03=implementierung k04=konstruktion k05=spezifikation k22=konstruktion k06=konstruktion k07=integration k08=wartung k09=konstruktion k10=studie k11=spezifikation k12=wartung k23=implementierung k13=integration k14=integration k15=wartung k16=wartung k17=spezifikation k18=integration k19=spezifikation k24=studie k20=wartung k21=implementierung | unsicher: k03 k22 k09 k23 -->
