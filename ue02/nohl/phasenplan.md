# Phasenplan — Terminplaner für die THM

Kürzel: nohl

## Studie

**Ergebnis der Phase:** …

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis der Phase:** …

- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen

## Systemkonstruktion

**Ergebnis der Phase:** …

- Datenbank, Programmiersprache und Web-Framework auswählen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt

## Implementierung

**Ergebnis der Phase:** …

- Die Komponente „Benachrichtigung“ programmieren
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen

## Integration & Einführung

**Ergebnis der Phase:** …

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen

## Wartung

**Ergebnis der Phase:** …

- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen
- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen** (Systemspezifikation): …
- **Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt** (Systemkonstruktion): …

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=implementierung k09=konstruktion k10=spezifikation k11=wartung k12=implementierung k23=konstruktion k13=studie k14=spezifikation k15=implementierung k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=konstruktion k20=integration k21=implementierung | unsicher: k10 k24 -->
