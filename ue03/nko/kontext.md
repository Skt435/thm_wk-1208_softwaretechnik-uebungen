# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

<!-- Mindestens sechs Stakeholder, je mit einem Satz dazu, worauf sie
     Einfluss haben. -->

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Lehrende | Sie haben Einfluss auf das Angebot, die zeitliche Vergabe und die Kapazitäten ihrer Sprechstunden und Prüfungstermine. |
| Studierende | Sie haben Einfluss auf die Buchung der Termine sowie auf die Anforderungen an die Benutzerfreundlichkeit (Usability). |
| Sekretariate | Sie haben Einfluss auf die organisatorische Überwachung, Koordination und Vertretungsregelungen im Fachbereich. |
| Hochschulleitung & IT-Verwaltung | Sie haben Einfluss auf Vorgaben zum Datenschutz, die Integration des Hochschulkontos und die IT-Sicherheitsrichtlinien. |
| Entwicklerteam | Sie haben Einfluss auf die technische Architektur, die Implementierung der API für KI-Agenten und die iCal-Export-Funktion. |
| Datenschutzbeauftragter | Sie haben Einfluss auf die datenschutzkonforme Ausgestaltung (DSGVO) bei der Verarbeitung von Personendaten. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Hochschulkonto (IDM) | System im Betrieb | Dient zur Authentifizierung und Autorisierung aller Nutzer (Lehrende, Studierende, Sekretariate) beim Login. |
| Vorlesungs- und Prüfungszeitraum | Ereignis | Gibt den zeitlichen Rahmen und die Fristen vor, in denen Termine angeboten und gebucht werden müssen. |
| iCal-Kalender-Clients | System im Betrieb | Externe Kalenderanwendungen der Benutzer, welche die heruntergeladenen iCal-Dateien importieren und verarbeiten. |
| KI-Agenten | System im Betrieb | Automatisierte Software-Clients, die über die Programmierschnittstelle (API) mit dem Terminplaner interagieren. |
| Datenschutz- und Nutzungsrichtlinien | Dokument | Rechtliche Vorgaben der THM, die bei der Speicherung und Verarbeitung der Termindaten zwingend eingehalten werden müssen. |

## Irrelevante Umgebung
- Mensa-Speiseplan der THM — Steht in keinem funktionalen oder organisatorischen Zusammenhang mit der Verwaltung und Vereinbarung von akademischen Sprech- und Prüfungsterminen.
- Ausleihsystem der Hochschulbibliothek — Dient der Medienverwaltung und hat keinerlei Schnittstellenrelevanz oder Einfluss auf den Buchungsablauf im Terminplaner.

