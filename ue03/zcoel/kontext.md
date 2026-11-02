# Kontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat der Stakeholder Einfluss? |
|---|---|
| Studierende | Wollen Termine schnell am Handy buchen können und eine einfache UI/übersicht für die Termine haben. |
| Lehrende / Dozenten | Müssen Termine festlegen können: Zeiten und länge für Sprechstunde oder Prüfungen. |
| Sekretariat | Muss bei Bedarf Termine für Professoren verwalten oder verschieben können, falls jemand krank wird. |
| THM-IT / ITS | Bestimmt, auf welchen Servern das Ganze läuft und sorgt dafür, dass der THM-Login funktioniert. |
| Datenschutzbeauftragte | Achtet darauf, dass Namen und Buchungsgründe nicht öffentlich für alle sichtbar sind (wie beispielsweise die Bonuspunkte :P). |
| Fachschaft | Gibt Feedback: BSPW. wenn Studierende mit der Bedienung oder den Abläufen unzufrieden sind. |

## Systemkontext

| Aspekt | Art | Warum gehört der Aspekt zum Kontext? |
|---|---|---|
| Studierende und Dozenten | Person | Sie sind die direkten Nutzer, die Termine anlegen, buchen oder wieder absagen. |
| THM-Login (LDAP / SSO) | System im Betrieb | Sorgt dafür, dass man sich mit der normalen Hochschul-Kennung einloggen kann. |
| Semesterbeginn | Ereignis | Alle wollen fast gleichzeitig Termine machen, was das System aushalten muss. |
| Termin absagen | Prozess | Regelt, was passiert, wenn jemand doch nicht kann und gibt besetzten Platz wieder frei. |
| Prüfungsanmeldung | Dokument | Gibt feste Fristen vor, bis wann Anmeldungen für die Prüfungen erledigt sein müssen. |

## Irrelevante Umgebung

- Mensa-Speiseplan: Dient ausschließlich zur reinen Information, was es in der Mensa zu essen gibt, und hat keine Abhängigkeiten oder Relevanz für Termine.
- Bibliotheks-Öffnungszeiten: Zeigt nur an, wann die Bibliothek aufhat, hat aber technisch und organisatorisch nichts mit Sprechstundenterminen zu tun.
