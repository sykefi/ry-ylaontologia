---
layout: "default"
title: "Rakennetun ympäristön yläontologia"
description: ""
id: "ylaontologia"
---
# Rakennetun ympäristön yläontologia

Ontologia on tuotettu RYTJ:n käsite- ja loogisen tietomallin tuottamisen ohessa, ja se on tämän version kuvaamassa muodossa karkea luonnos RYTJ:n hallinnoimien rakennetun ympäristön tietojen formaalista semanttisesta rakenteesta OWL-ontologiana. Tätä mallia tulkitessa tulee huomioida, että ontologia on tuotettu hyvin nopealla aikataululla laajasta lähtöaineistosta ja sitä ei ole validoitu tuotantokäyttöön.

Ontologiaan ei ole vielä yhdistetty suoraan SKOS-muotoista RYTJ-sanastoa kuvaamaan luokkia vastaavia käsitteitä; käsitevastaavuudet voi tarkistaa [Y-alustalta](http://uri.suomi.fi/terminology/rytj/). Rakenteen vastaavuus prosesseja, niiden osia ym. kuvaavien käsitteiden osalta ei ole identtinen johtuen käytetyn PROV-O-ontologian ylärakenteiden noudattamisesta.

Ontologian dokumentaatio on generoity pyLODElla ontdoc-profiilia. Valitettavasti kyseinen profiili ei oletuksena kuvaa kompleksisempia ominaisuusrajoitteita (esim. xsd:pattern) eikä esitä datatyyppejä. Profiilista ehdittiin projektin aikana tehdä minimaalisesti päivitetty versio joka ei kuitenkaan vielä kata näitä puutteita.

Ontologian tuottamisessa on selvitetty W3C:n Time-ontologian käyttöä ajallisten entiteettien kuvailuun, OGC:n GeoSPARQL-ontologian käyttöä spatiaalisten entiteettien kuvailuun, W3C:n PROV-O-ontologian käyttöä subjektien, toiminnan ja toiminnan kohteiden välisen tapahtuma- ja muutoshistorian kuvailuun, sekä IFCOWL-ontologian käyttöä rakennustietovarannon entiteettien määrittämiseen. Näistä GeoSPARQL, PROV-O ja Time ovat alustavasti ehdotusluonteisesti käytössä maankäyttökohteille sekä prosesseille. GeoSPARQL:stä käytössä on vakaa 1.0-versio, sillä 1.1 on epävakaa ja edelleen aktiivisesti työn alla. Tämä kuitenkin tarkoittaa sitä, että tämä malli ei pääse hyötymään lukuisista 1.1:een tehdyistä parannuksista ja korjauksista.

Tämän ontologian tulkitsemiseen suositellaan seuraavia helppolukuisia teoksia: 1) Moreau, L., & Groth, P. (2013). Provenance: An introduction to PROV. Morgan & Claypool. https://doi.org/10.2200/S00528ED1V01Y201308WBE007 2) Uschold, M. (2018). Demystifying OWL for the Enterprise. Synthesis Lectures on the Semantic Web: Theory and Technology, 8(1), i–237. https://doi.org/10.2200/S00824ED1V01Y201801WBE017 3) Lappalainen, M. (2014). Yläontologiat ja yleisen suomalaisen ontologian ylärakenne: ONKI-projektin toteuttamat muutokset. Kansalliskirjasto. http://urn.fi/URN:ISBN:978-951-51-0347-5

Synkronointi RYTJ-käsitemallin kanssa tehty viimeksi 26.11.2021