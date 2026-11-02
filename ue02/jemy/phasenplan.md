# Phasenplan — Terminplaner für die THM

Kürzel: jemy

## Studie

**Ergebnis der Phase:** Lastenheft

- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Aufwand schätzen und einen Meilensteinplan vorschlagen
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Systemspezifikation

**Ergebnis der Phase:** Pflichtenheft

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden

## Systemkonstruktion

**Ergebnis der Phase:** fachliche und technische Konstruktion

- Datenbank, Programmiersprache und Web-Framework auswählen
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert

## Implementierung

**Ergebnis der Phase:** Softwarekomponente

- Die Komponente „Benachrichtigung“ programmieren
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis der Phase:** getestetes produktiives Gesamtsystem

- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt

## Wartung

**Ergebnis der Phase:** Fehlerbeseitigung, Beratung,Anpassungen...

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt** (Implementierung): Implementierung

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=konstruktion k06=konstruktion k07=studie k08=integration k09=konstruktion k10=spezifikation k11=wartung k12=implementierung k23=konstruktion k13=studie k14=spezifikation k15=konstruktion k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=implementierung k20=integration k21=studie | unsicher: k24 -->
