# Aufgabe 1: Stakeholder und Systemkontext

## 1. Stakeholder
| Stakeholder | Einfluss auf die Anforderungen |
| :--- | :--- |
| **Studierende** | Wollen vor allem, dass die App unterwegs auf dem Handy flüssig läuft und man schnell Termine buchen kann. |
| **Dozenten** | Brauchen eine einfache Möglichkeit, freie Zeiten einzutragen und Anfragen ohne großen Aufwand zu verwalten. |
| **IT-Team / Rechenzentrum** | Achten darauf, dass das System stabil läuft, nicht abstürzt und sicher mit dem Hochschul-Login verbunden ist. |
| **Sekretariat** | Muss Überschneidungen vermeiden und Raumreservierungen im Blick behalten, falls Termine vor Ort stattfinden. |
| **Datenschutzbeauftragte** | Passen auf, dass die Daten der Studierenden sicher gespeichert werden und alles nach DSGVO abläuft. |
| **Prüfungsamt** | Legt fest, welche Fristen eingehalten werden müssen, damit gebuchte Termine offiziell gültig sind. |

## 2. Systemkontext
| Kontextaspekt | Typ | Begründung |
| :--- | :--- | :--- |
| **THM-Login (SSO)** | System im Betrieb | Hierüber melden sich alle an, damit das System weiß, wer Student und wer Dozent ist. |
| **Prüfungsphase** | Ereignis | In diesem Zeitraum nutzen extrem viele Leute gleichzeitig die Seite, worauf der Server vorbereitet sein muss. |
| **Outlook / Kalender** | System im Betrieb | Gebuchte Termine sollen automatisch im eigenen Kalender auf dem Handy oder Laptop auftauchen. |
| **Prüfungsordnung** | Dokument | Darin stehen die Regeln, wie lange im Voraus man Termine buchen oder wieder absagen darf. |
| **Sprechstunden-Ablauf** | Prozess | Definiert, wie genau der Weg von der Terminfrage bis zur Bestätigung durch den Dozenten verläuft. |

## 3. Irrelevante Umgebung
1. **Mensa-Speiseplan**: Hat absolut nichts mit der Buchung von Sprechstunden oder Prüfungsterminen zu tun.
2. **Bibliotheks-System**: Die Ausleihe von Büchern läuft komplett getrennt und beeinflusst die Terminplanung nicht.
