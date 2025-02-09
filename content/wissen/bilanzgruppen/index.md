---
draft: true

title: "Österreichisches Strommarktmodell"
description: "Ein Überblick über Bilanzgruppen und Ausgleichsenergie."
topics: ["Bilanzgruppen"]
authors:
  - "fackerl"
series: ["Strommärkte"]
series_order: 9
weight: 9
---

<!-- Nummerierung überarbeiten -->
<!-- S. 1 festlegen (EOM?) -->
<!-- Bild von Econtrol einfügen? -->

## Bilanzgruppen

Bilanzgruppen sind virtuelle Gruppen, in denen Stromerzeuger und -lieferanten zusammengefasst werden. Jede Bilanzgruppe ist verpflichtet, den Verbrauch und die Erzeugung von Strom innerhalb der Gruppe ausgeglichen zu halten. Dazu erstellt sie Prognosen für die erwartete Stromerzeugung und den Verbrauch für den Folgetag.[^1] [^3]

### Ausgleichsenergie

Kommt es zu einer unvorhergesehenen Abweichung von der Prognose, die die Bilanzgruppe nicht selbst ausgleichen kann, muss die fehlende oder überschüssige Energiemenge durch Ausgleichsenergie gedeckt werden. Diese gleicht die Differenz zwischen geplanter und realer Einspeisung bzw. Entnahme aus dem Netz aus.

In der Regelzone Österreich gibt es zahlreiche Bilanzgruppen. Der Saldo der Ausgleichsenergie über alle Bilanzgruppen ergibt den Bedarf an [Regelenergie](./wissen/regelenergie/index.md), für welchen der Regelzonenführer <abbr title="Austrian Power Grid">APG</abbr> zu sorgen hat. Die Summe der benötigten Ausgleichsenergie kann dabei deutlich höher sein als die tatsächlich eingesetzte Regelenergie, da sich einige Abweichungen innerhalb der Bilanzgruppen gegenseitig ausgleichen können. Unabhängig davon, wie viel Regelenergie am Ende tatsächlich eingesetzt wird, muss jede Bilanzgruppe für ihre eigene Prognoseabweichung Ausgleichsenergie bezahlen. Jede Bilanzgruppe hat einen [Bilanzgruppenverantwortlichen](./wissen/akteure/index.md), der die Bilanzgruppe vertritt und für die angefallene Menge an Ausgleichsenergie haftet.[1] [^2] [^3]

Die zentrale Ermittlungs- und Verrechnungsstelle für Ausgleichsenergie im österreichischen Strommarkt ist die Power Clearing and Settlement AG (<abbr title="Austrian Power Clearing and Settlement AG">APCS</abbr>), welche als [Bilanzgruppenkoordinator](./wissen/akteure/index.md) (<abbr title="Bilanzgruppenkoordinator">BKO</abbr>) bezeichnet wird. Die <abbr title="Austrian Power Clearing and Settlement AG">APCS</abbr> ermittelt und verrechnet die Differenz zwischen geplanter und tatsächlicher Netzeinspeisung bzw. -entnahme für jede Bilanzgruppe.[^4] [^1]
<!-- Unklar: ist APCS der einzige BKO in Österreich? -->

### Unterschied Ausgleichsenergie - Regelenergie

Zusammengefasst gleicht Ausgleichsenergie die Prognoseabweichungen einzelner Bilanzgruppen aus und wird diesen in Rechnung gestellt. [Regelenergie](./wissen/regelenergie/index.md) hingegen dient dazu, das gesamte Stromnetz stabil zu halten, wenn es aufgrund der einzelnen Abweichungen in den Bilanzgruppen zu einem Ungleichgewicht in der gesamten Regelzone kommt. Vereinfacht gesagt ist die Abweichung der Prognose in einer Bilanzgruppe die Ausgleichsenergie und die Prognoseabweichung in der gesamten Regelzone die Regelenergie.[^2]

### Weitere Informationen

- Beschaffung der Ausgleichsenergie: [AGCS: Ausgleichsenergiebeschaffung](https://www.agcs.at/de/ausgleichsenergie)
- Die genauen Regeln und Bedingungen sind in den [Allgemeinen Bedingungen des Bilanzgruppenkoordinators](https://www.apcs.at/de/regelwerk/marktregeln/aktuelle_version) festgelegt

<!-- Link zu Übersicht welche Bilanzgruppen es gibt wäre nice -->

[^1] [APG: Österreichisches Strommarktmodell](https://markt.apg.at/strommarkt/oesterreichisches-strommarktmodell/)
[^2] [E-Control: Regelreserve und Ausgleichsenergie](https://www.e-control.at/marktteilnehmer/strom/strommarkt/regelreserve-und-ausgleichsenergie)
[^3] [Next Kraftwerke: Ausgleichsenergie](https://www.next-kraftwerke.at/wissen/ausgleichsenergie)
[^4] [APCS: Aufgaben](https://www.apcs.at/de/aufgaben)
