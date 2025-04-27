---
title: "Sekundärregelreserve"
description: ""
topics: ["Sekundärregelreserve"]
series: ["Systemdienstleistungen"]
series_order: 1
authors: [fackerl]
---

<!--more-->

Kommt es im Stromnetz zu Abweichungen vom Sollwert von 50 Hertz, wird zunächst die [Primärregelreserve](/wissen/regelreserve/primärregelreserve/) aktiviert. Hält die Störung länger als 30 Sekunden an, folgt die Aktivierung der Sekundärregelreserve (<abbr title="Sekundärregelreserve">SRR</abbr>), auch Sekundärregelleistung oder Sekundärreserveleistung (<abbr title="Sekundärreserveleistung">SRL</abbr>) genannt. Sie ist der <abbr title="Primärregelreserve">PRR</abbr> nachgeordnet und entlastet diese, indem sie dafür sorgt, dass die <abbr title="Primärregelreserve">PRR</abbr> wieder für ihre eigentliche Aufgabe zur Verfügung steht. Die <abbr title="Sekundärregelreserve">SRR</abbr> muss innerhalb von fünf Minuten vollständig aktiviert werden. [^APCS] [^APG]
<!--wie lange dann aktiv? -->

Die <abbr title="Sekundärregelreserve">SRR</abbr> wird automatisch über eine bidirektionale Datenverbindung mit dem Leitsystem der <abbr title="Austrian Power Grid">APG</abbr> aktiviert. Ein Leistungsfrequenzregler sorgt dafür, dass die Abrufe der <abbr title="Sekundärregelreserve">SRR</abbr> gleichmäßig auf die bezuschlagten Anbieter:innen verteilt werden. Dafür geeignet sind gut regelbare und vollautomatisch per Fernwirkeinrichtung schaltbare Kraftwerke, wie etwa Pumpspeicherkraftwerke, Gasturbinen sowie auch [virtuelle Kraftwerke](/wissen/virtuelle-kraftwerke/) aus Biogas-, Wasserkraft und Power-to-X-Anlagen. [^kraftwerke_sekundär]

Die Beschaffung der <abbr title="Sekundärregelreserve">SRR</abbr> findet über Ausschreibungen statt, die sich in [Leistungs- und Energieausschreibungen](/wissen/regelreserve/) aufteilen. [^kraftwerke_sekundär] Diese finden zwar national innerhalb der Regelzone Österreich statt, der eigentliche Abruf der Regelenergie erfolgt jedoch über eine länderübergreifende Kooperation im Zuge von [PICASSO](https://www.entsoe.eu/network_codes/eb/picasso/). Die bezuschlagten Angebote werden zu einer gemeinsamen Merit-Order-Liste zusammengeführt, welche als Common Merit-Order-List (<abbr title="Common Merit-Order-List">C-MOL</abbr>) bezeichnet wird. Diese ermöglicht, unter Beachtung der vorhandenen Übertragungskapazitäten, eine europaweite kostenoptimierte Aktivierung von Regelreservearbeit.[^regelleistung.net] [^APG_picasso] [^kraftwerke_sekundär] Für die Leistungsausschreibung der <abbr title="Sekundärregelreserve">SRR</abbr> sind in der österreichischen Regelzone ± 225 MW vorgesehen. [^APG_sekundär]

Reicht die automatisch aktivierte <abbr title="Sekundärregelreserve">SRR</abbr> nicht aus, um das entstandene Ungleichgewicht auszugleichen, wird zusätzlich die manuell aktivierte [Tertiärregelreserve](wissen/regelreserve/tertiärregelreserve/) eingesetzt. [^APG]
<!--nach 15 min ?  -->
<!--verlinkung zur main Regelreserve-Seite  -->

[^regelleistung.net]: [Regelleistung.net: PICASSO & IGCC (aFRR Arbeitsmarkt)](https://www.regelleistung.net/de-de/Europ%C3%A4ische-Kooperationen/PICASSO-IGCC-aFRR-Arbeitsmarkt)
[^APG_picasso]: [APG: PICASSO/IGCC](https://markt.apg.at/netz/netzregelung/sekundaerregelung/picasso-igcc/)
[^kraftwerke.at]: [Next Kraftwerke: Regelenergie in Österreich](https://www.next-kraftwerke.at/wissen/regelenergie)
[^kraftwerke_sekundär]: [Next Kraftwerke: Sekundärregelung](https://www.next-kraftwerke.at/wissen/sekundaerregelung-srl)
[^A1]: [A1 Energy Solutions: Regelenergie kurz erklärt](https://www.a1energysolutions.at/regelenergie-pool/)
[^econtrol]: [E-Control: Marktbasierte Beschaffung Regelreserve](https://www.e-control.at/industrie/strom/strommarkt/marktbasierte-beschaffung-regelreserve#:~:text=In%20%C3%96sterreich%20erfolgt%20die%20vollst%C3%A4ndig,werden%20Erzeugern%20und%20Bilanzgruppen%20verrechnet)
[^APG]: [APG: Netzregelung](https://markt.apg.at/netz/netzregelung/)
[^APG_sekundär]: [APG: Sekundärregelung (SRR)](https://markt.apg.at/netz/netzregelung/sekundaerregelung/)
[^APCS]: [APCS: Regelenergie](https://www.apcs.at/de/regelenergie)
