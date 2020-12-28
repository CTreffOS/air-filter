# Luftfilter bauen

---

## Einführung
<!-- Timo -->

---

### Warum Luftfilter?
* Hauptübertragungsweg: Tröpfchen/Aerosole [rki20]
<!-- Tröpfchen sinken schnell zum Bodem -->
<!-- Aerosole über längere Zeit in der Luft schweben und in geschlossenen Räumen verteilen -->
* Umweltbundesamt: Stoßlüften in Schulen alle 20 min für mindestens 3-5 min [uba20]
* Ähnliche Empfehlungen für Besprechungsräume [dguv20]
* Nachteile: Schwierig durchzuhalten, Räume kühlen stark runter [kfh20]

---

### Ziele
* Virenbelastung in Raumluft senken
    * Aerosole aus der Luft filtern oder Viren unschädlich machen
* Mobiles Filtersystem (kein Einbausystem)
* Günstig zu produzieren
* Leicht zu bedienen
* Wenig störende Geräusche

---

### Ziele 2

* Komplette Luftfilterung mindestens 3x pro Stunde
<!-- aller mindestens, lieber häufiger, aber je nach Szenario, manche Experten sagen auch 6x/h -->
* Für verschiedene Anforderungen: Klassenzimmer, Büro, Tee-Küche, Familienevent, ...
    * Nach jeweiliger Analyse, Hilfe bei [zeit20]
* Trotz Luftfilter Ansteckungsgefahr nicht unterschätzen

---

## Luftfiltertypen

---

### EPA/HEPA/ULPA Filter
<!-- Timo -->
* Schwebstofffilter Klassen
* Getestet bei 0,1 – 0,3 μm Partikel bei 0,45 m/s [EN1822]:

| Klasse   | Abscheidegrad |
| -------- | --------- |
| EPA E11  | ≥ 95      |
| EPA E12  | ≥ 99,5    |
| HEPA H13 | ≥ 99,95   |
| HEPA H14 | ≥ 99,995  |
| ULPA U15 | ≥ 99,9995 |

---

#### HEPA Filter

* Bauformen:
    * Rechteckige Platte
    * Hohlzylinder
* Lebensdauer:
    * Je nach Produkt ca. 6 Monate
    * Bei stärkerer Nutzung weniger
* Luftdruck benötigt, um Luft durch Filter zu drücken/ziehen

---

### UV Lampen
<!-- Magnus -->
* Bauformen:
    * Glühbirne
    * Röhre
    * UV-C (280–100 nm)
        * benötigte Energie: 37 J/m² (99,9% Reduktion) [mwt20]
    <!-- UV-A 315–380nm -->
    <!-- UV-B 280–315nm -->
* Lebensdauer:
    * mindestens 1 mal im Jahr austauschen
* UV-Strahlung kann Haut und Augen schädigen [who20]

---

## Filterstandorte
<!-- Überschrift überdenken. Luftfilterverteilung, ... -->

---

### Ein starker Luftfilter
![](https://md.darmstadt.ccc.de/uploads/upload_3436b060e6a42ec8a6a6178d659e13f0.png)


[lfb20]

---

### Mehrere kleine Luftfilter
![](https://md.darmstadt.ccc.de/uploads/upload_7875adee4b4805d0462ffb0a48ba3abf.png)
[lfb20]

---

## Entwickelte Systeme

---

### Airwolf UV Lampe
<!-- Magnus -->
* Projekt auf github.com [mwc20]
* Ziel: Firmen, Schulen, Kindergärten, (alle)
* Luft wird längs an den UV-C Röhren vorbei gezogen


---

### 3D Druck/Holz und Case Variante
![](https://md.darmstadt.ccc.de/uploads/upload_34b8fe62d7fb4b50a8ab8de1a524ec2a.png)

[mwc20]

---

#### Kleines 3d-gedrucktes Modell

* PETG oder ASA und Holz
* Materialkosten: 175€
* Durchsatz: 380 m³/h

* 4x 55W UV-C
    * 120 J/m²
* 4 oder 8 Lüfter

---

### HEPA Klassenzimmer Luftfilter
<!-- Timo -->
* Projekt auf hackster.io [hhf20]
* Ziel: Klassenzimmer
* 4 mal 30x24cm Rechteckige HEPA Filter
* Starker Lüfter zieht luft nach oben

---

#### Varianten
![3 Varianten](https://md.darmstadt.ccc.de/uploads/upload_a9a3649649a3361565c00b3dd6608b97.png)

---

#### Variante A
* 230 V Wechselstromventilator
* Geräuschentwicklung "OK"
* Nicht regelbar

---

#### Variante A Mk III
* Variante mit bestem Preis-Leistungs-Verhältnis
* Gleichstromventilator (Motorkühlungsventilator) mit 12 V
* Sehr Laut
* Kann leicht gedrosselt werden

---

#### Variante B
* Idee PC-Lüfter sind günstig
* Verwendet 4 PC-Lüfter
* Lüfter mit hohem statischen Druck -> teuer
* Kann mit entsprechenden Lüftern leise sein

---

#### Vergleich

|  Lüfter            | Variante A | Variante A Mk III |Variante B |
| ------------------ | ---------- | ----------------- | --------- |
| Durchsatz (m³/h)   | 770        | 1500, 600, 350    | 770, 450  |
| Geräusch (dB)      | 48         | 63, 40, 30        |           |
| Materialkosten (€) | 120        | 135               | 230, 150  |


---

### Kleine verteilte Luftfilter
<!-- Unsere Version -->

---

#### Idee
<!-- Magnuns -->
* Viele kleine günstige Luftfilter
* gerichteten Luftstrom
    * gefilterte Luft soll nicht direkt wieder gefiltert werden
* Einfach zu bauen
    * runde HEPA Filter
    * 3D Druck Teile
* Verschiedene Versionen:
    * besonders leise
    * viel Durchsatz

---

#### PC-Lüfter Versionen

##### leise
Preis: 19€ (Filter) + 10€ (Lüfter) + 5€ (Netzteil) + 2€ (Rohr) + 3€ (gedruckte Teile) + 2€ (Sonstiges)  = 41€

##### stark
Preis: 19€ (Filter) + 15€ (Lüfter) + 5€ (Netzteil) + 2€ (Rohr) + 3€ (gedruckte Teile) + 2€ (Sonstiges) = 46€


---

#### Bad-Lüfter Version
Preis: 19€ (Filter) + 19€ (Lüfter) + 7€ (gedruckte Teile) + 2€ (Sonstiges) = 47€

---

#### Zusammenfassung
<!-- Timo -->
|  Lüfter            | PC-Lüfter stark | PC-Lüfter leise | Bad Lüfter |
| ------------------ | --------------- | --------------- | ---------- |
| Durchsatz (m³/h)   | 74,3            | 36,4            | 124,7      |
| Geräusch (dB)      | 32              | 25              | 31         |
| Materialkosten (€) | 44              | 39              | 42         |
| Druckdauer (h)     | 11              | 11              | 29         |

---

#### Messverfahren
* Durchsatz
    * Ansauggeschwindigkeit am Filter messen:
        * Air Flow Geschwindigkeitsmesser
        * An 12 Stellen
    * Filteroberfläche
* Geräusch
    * Smartphone App
    * 1 m Abstand
    * Nicht sehr Aussagekräftig
        * Gegenüber anderen Messungen

---

## Beispiel Szenarien

---

### 2 Personen Büro
* 5x4 meter (20 m²)
* [zeit20]:
    * Ohne Lüften: 53% Wahrscheinlichkeit
    * Stoßlüften: 24% Wahrscheinlichkeit
* Deckenhöhe 2,4 m -> 48 m³ Luft
* Austausch 3x pro Stunde -> 144 m³/h
* 2x Version PC-Lüfter stark
  (Materialkosten unter 90 €)
    * Empfehlung: Trotzdem 1x pro Stunde Stoßlüften

---

### Gemeinschaftsküche WG
* Nie 2 Personen gleichzeitig
* 3x5 meter (15 m²)
* Deckenhöhe 2,4 m -> 36 m²
* 1x Version Bad (Materialkosten 42 €)
    * 17 min komplette Luft gefiltert

---

### Meeting Raum
* 6x5 meter (30 m²)
* 8 Personen an einem Tisch
* Meeting maximal 30 min (Rededauer 90%)
* [zeit20]:
    * 5% Wahrscheinlichkeit
* 3 mal leise PC-Lüfter Variante auf dem Tisch
    * Empfehlung: Trotzdem Mund-Nasen-Schutz tragen (direkte Tröpfchenübertragung möglich)

---

## Quellen und Links
* \[dguv20]: https://www.dguv.de/de/mediencenter/pm/pressearchiv/2020/quartal_3/details_3_405890.jsp
* \[EN1822]:  DIN EN 1822-1:2019-10 Schwebstofffilter (EPA, HEPA und ULPA) - Teil 1: Klassifikation, Leistungsprüfung, Kennzeichnung
* \[hhf20]: https://www.hackster.io/hhf/klassenzimmer-antivirus-raumluftfilter-4b0891

---

* \[kfh20]: https://www.tojiro.de/media/raumluftreiniger.pdf
* \[lfb20]: http://www.luftfilterbau.de/de/produkte/anwendungsbereiche/covid-19-pandemie/hs-airifyre-350-raumluftreiniger-fuer-schulen-hepa.html
* \[mwc20]: https://github.com/MaibornWolff/clean-air
* \[mwt20]: https://github.com/MaibornWolff/clean-air/blob/main/documentation/theory.pdf

---

* \[rki20]: https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Steckbrief.html
* \[uba20]: https://www.umweltbundesamt.de/richtig-lueften-in-schulen
* \[who20]: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public/myth-busters#uv
* \[zeit20]: https://www.zeit.de/wissen/gesundheit/2020-11/coronavirus-aerosole-ansteckungsgefahr-infektion-hotspot-innenraeume

<!--
Genutzten Quellen in [MWT20]:
* https://www.doi.org/10.3205/dgkh000343
* https://www.doi.org/10.1101/2020.06.05.20123463
* http://doi.org/10.1101/2020.05.31.20118588
-->

---

## Beteiligung/Ideen erwünscht

* https://github.de/CTreffOS/air-filter
* Mastodon
    * @mschieder@osna.social
    * @cyberto@osna.social
* Twitter:
    * @mschieder1
    * @derCyberto

