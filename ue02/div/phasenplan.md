# Phasenplan — Terminplaner für die THM

Kürzel: div

## Studie

**Ergebnis der Phase:** lastenheft

- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis der Phase:** pflichtenfeft

- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Datenbank, Programmiersprache und Web-Framework auswählen

## Systemkonstruktion

**Ergebnis der Phase:** entwurf

- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen

## Implementierung

**Ergebnis der Phase:** code

- Die Komponente „Benachrichtigung“ programmieren
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten

## Integration & Einführung

**Ergebnis der Phase:** fertige Software

- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt

## Wartung

**Ergebnis der Phase:** Korrigierte und weiterentwickelte Versionen des Systems

- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen** (Wartung): …
- **Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen** (Wartung): …
- **Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden** (Systemspezifikation): …

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=implementierung k03=integration k04=wartung k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=integration k09=spezifikation k10=wartung k11=wartung k12=integration k23=implementierung k13=studie k14=spezifikation k15=konstruktion k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=integration k20=integration k21=integration | unsicher: k10 k11 k19 -->
