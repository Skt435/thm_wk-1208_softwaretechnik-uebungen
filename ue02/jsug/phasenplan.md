# Phasenplan — Terminplaner für die THM

Kürzel: jsug

## Studie

**Ergebnis der Phase:** Lastenheft: Analyste IST-Situation, Anforderungen, Lösungsvarianten, Empfehlung, Vorschlag eines Projektplans

- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis der Phase:** Fachkonzept: Beschreibung der fachlichen Anforderungen

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Systemkonstruktion

**Ergebnis der Phase:** Komponenten und Technologien werden festgelegt

- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Datenbank, Programmiersprache und Web-Framework auswählen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert

## Implementierung

**Ergebnis der Phase:** Programmierung der Komponenten

- Die Komponente „Benachrichtigung“ programmieren
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis der Phase:** Das System wird in Betrieb genommen, nachdem die Anforderungen geprüft wurden

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen

## Wartung

**Ergebnis der Phase:** Fehler wurden beseitigt, Change Requests durchgeführt

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Datenbank, Programmiersprache und Web-Framework auswählen** (Systemkonstruktion): Kann zur Studie gehören, jedoch auch zur Systemkonstruktion
- **Aufwand schätzen und einen Meilensteinplan vorschlagen** (Studie): Gehört eher zur Projektplanung

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=integration k09=konstruktion k10=integration k11=wartung k12=implementierung k23=konstruktion k13=studie k14=studie k15=konstruktion k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=integration k20=integration k21=spezifikation | unsicher: k09 k13 -->
