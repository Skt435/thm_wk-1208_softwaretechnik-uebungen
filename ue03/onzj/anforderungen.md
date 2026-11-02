
# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Studierende müssen verfügbare Sprechstundentermine einsehen und eine Buchungsanfrage stellen können. | Studierende | FA |
| A02 | Lehrende müssen eigene Zeitfenster für Sprechstunden freigeben, sperren und eingehende Buchungsanfragen bestätigen oder ablehnen können. | Lehrende | FA |
| A03 | Studierende dürfen ausschließlich ihre eigenen Buchungen einsehen und verwalten, sofern ihnen keine zusätzlichen Berechtigungen zugewiesen wurden. | Studierende | FA |
| A04 | Der Terminplaner muss eine monatliche Verfügbarkeit von mindestens 99,5 % außerhalb angekündigter Wartungsfenster erreichen. | Studierende, Lehrende | QA |
| A05 | Bei 500 gleichzeitig aktiven Nutzern müssen mindestens 95 % aller Seitenaufrufe innerhalb von drei Sekunden vollständig geladen werden. | Studierende, THM-Rechenzentrum | QA |
| A06 | In einem Benutzbarkeitstest müssen mindestens 90 von 100 Erstnutzenden innerhalb von drei Minuten ohne fremde Unterstützung einen verfügbaren Sprechstundentermin finden können. | Studierende | QA |
| A07 | Die Authentifizierung muss über das bestehende Hochschulkonto der THM erfolgen, sodass keine separate Registrierung erforderlich ist. | THM-Rechenzentrum | RB |
| A08 | Die Verarbeitung personenbezogener Daten muss den geltenden Datenschutzvorschriften, insbesondere der DSGVO, entsprechen. | Datenschutzbeauftragte der THM | RB |

## Eine Anforderung, die niemand ausgesprochen hat

A03: Die Beschränkung des Zugriffs auf eigene Buchungen wurde im ursprünglichen Gespräch nicht ausdrücklich erwähnt, da der Schutz persönlicher Termininformationen vermutlich als selbstverständlich angesehen wurde. Dennoch muss diese Berechtigungsregel berücksichtigt werden, um unbefugte Zugriffe auf personenbezogene Daten zu verhindern.
