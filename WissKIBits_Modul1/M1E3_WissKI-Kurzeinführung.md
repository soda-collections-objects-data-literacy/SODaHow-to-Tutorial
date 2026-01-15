<!--
author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk ()

email: c.hastik@igsd-ev.de

email: g.schwenk@igsd-ev.de

version:  v1

language: DE

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/liascript-oers/refs/heads/main/resources/SODa-Logo_full.svg
link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits/refs/heads/main/soda.css

license: CC BY 4.0

comment: Dieser Text erscheint als Info innerhalb der Liascript-Module oben rechts hinter dem (i) und sollte den Inhalt des Moduls kurz beschreiben. Vorschlag: Mirco-Content zum Lernziel "Lernende können FAIR-Prinzipien erläutern". Dieses Modul ist Teil eines Einführungskurses zum Forschungsdatenmanagement, der von “OER.Net UAG FDM-Basiskurs” auf Grundlage der Lernzielmatrix zum FDM entwickelt wurde. Der Basiskurs entwickelt das Konzept der EduBricks weiter und ist als “Arbeitsgruppe 3: Einbettung und Vernetzung des modularen und skalierbaren Konzeptes” zudem Teil der NFDI-Sektion Education and Training.

title: Template für die Erarbeitung eines Micro-Contents anhand eines Lernziels für generischen FDM-Basiskurs

description: Dieses Template wurde als Vorlage für die Entwicklung von Microlearning-Content zum Themenbereich Forschungsdatenmanagement (FDM) in Orientierung an Lernzielen der [Lernzielmatrix zum Forschungsdatenmanagement (FDM)](https://zenodo.org/records/15025246) entwickelt.

keywords: FDM, Forschungsdatenmanagement, Forschungsdaten, Lernziel, Micro-Content

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: noch unveröffentlicht

LearningResourceType: SODa How-to-Tutorial

-->


# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung zum Diagramm – verstehen und erklären**

Einheit 3: **WissKI Kurzeinführung**  

**Dauer:** ~ 15 Min.

Lernziele 

* die fünf Stufen des 5-Sterne-Modells für offene Daten benennen. (LZ-ID 01_008_0158)
* FAIR Prinzipien benennen. (LZ-ID 01_007_0117)
* geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01_007_0121)
* die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikatiojnsinfrastruktur WissKI benennen und erläutern. (LZ-ID SODa_01_010_0191a und SODa_01_010_0192a)
* WissKI Pathbuilder als Werkzeuge zur Entwicklung von Ontologien bennenen und erläutern. (LZ-ID SODa_03_007_0803 und LZ-ID SODa_03_007_0804)
* die Methode der ereigniszentrierten Modellierung mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa_03_007_0785a)
* Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das sammlungsbezogene Forschungsdatenmanagement (FDM) ) mit der Wissenschaftlichen Kommunikationsinfrastuktur WissKI benennen. (LZ-ID SODa_01_010_0202)


---

## WissKI in Kürze

**WissKI** (Wissenschaftliche Kommunikations-Infrastruktur) ist:

* eine freie, quelloffene virtuelle Forschungsumgebung
* entwickelt für Kulturerbe- und Forschungsdaten
* basierend auf Semantic-Web-Technologien
* modular aufgebaut und standardorientiert.

WissKI wird u.a. am **Germanischen Nationalmuseum (GNM)** in Nürnberg eingesetzt —

* dem größten kulturhistorischen Museum im deutschsprachigen Raum
* das Maßstäbe für digitale Forschungsinfrastrukturen setzt.

WissKI ist **nicht nur** eine Sammlungsdatenbank –  es ist ein **semantisches Datenmanagementsystem für Linked Open Data (LOD)**  und unterstützt die FAIR-Prinzipien (
**Findable – Accessible – Interoperable – Reusable**)

![GNM](../assets/gnm.jpg)
![GNM innen](../assets/gnm_2.JPG)

---

## WissKI und Drupal 10

WissKI ist **keine eigenständige Software**.  

Es ist eine **semantische Erweiterung** des Content-Management-Systems **Drupal 10**.


![Drupal](../assets/drupal.JPG)

| Drupal stellt bereit …       | WissKI ergänzt …                        |
|-----------------------------|------------------------------------------|
| Benutzer- & Rollenverwaltung | Semantische Modellierung mit Ontologien  |
| Modulares Framework         | Pathbuilder für semantische Pfade        |
| REST- & JSON-Schnittstellen | RDF Triple-Store                  |
| Zugriffskontrolle           | SPARQL-Endpunkt                          |
| Mehrsprachige Oberfläche    | Veröffentlichung als Linked Open Data (LoD)    |

---

## Der WissKI Pathbuilder

Der **Pathbuilder** ist das **Herzstück von WissKI**.

WissKI arbeitet **nicht mit Tabellen**, sondern mit **ontologiebasierten Strukturen**.

Der Pathbuilder definiert:

* **Gruppen** → semantische Entitäten, z. B. Objekt, Person, Ort, Ereignis  
* **Pfade** → Beziehungen diese Entitäten, z. B. Objekt → wurde geschaffen von → Person  
* **Widgets** → automatisch generierte Eingabeformulare, deren Struktur aus der Semantik abgeleitet wird

So bleibt WissKI flexibel, ermöglicht semantische Konsistenz und ist in der Datenpflege bestmöglich Nutzendenunterstützend.

![Pathbuilder](../assets/pathbuilder.jpg)

---

## Semantisches Modellieren auf *WissKI-Art* = das Prinzip der ereigniszentrierten Modellierung (CIDOC CRM) erklären

In WissKI werden  **nicht nur Daten** gespeichert und erfasst, sondern **Bedeutung** modelliert.

Leitfrage:

> **Welche reale Beziehung besteht zwischen den Dingen?**

Beispiel aus dem Video:

* **Albrecht Dürer** → Person  
* wurde geboren in → **Nürnberg** (Ort)  
* zu → **einem bestimmten Zeitpunkt**  
* hatte eine Mutter → **Barbara Dürerin** (Person)  
* schuf → **Selbstbildnis** (Objekt)
* **Entstehungszeitpunkt** in einer **Quelle** erwähnt
* während → **seiner künstlerischen Schaffensperiode**  
* in → **Nürnberg**

Diese semantischen Bedeutungsaussagen lassen **einen Wissensgraphen** entstehen, ein Netzwerk verbundenen Informationen.

(Video: `../assets/semanticModelling.mp4`)

---

## Vorteile von WissKI Relevanz

* ermöglicht **wissensbasierte Modellierung** statt starrer Tabellenschemata
* stellt **Interoperabilität** durch etablierte Ontologien wie **CIDOC CRM** sicher
* unterstützt die **FAIR-Prinzipien**
* generiert **Eingabeformulare automatisch** auf Basis semantischer Pfade
* publiziert Daten als **Linked Open Data**
* bietet **leistungsfähige SPARQL-Abfragen**
* verbindet **konzeptionelle Klarheit** mit **technischer Umsetzung**.

---

## Die Semantik zentral in WissKi Nutzen

* **CIDOC CRM** definiert Konzepte & Beziehungen  
* **Semantische Pfade** bilden die Datenstruktur 
* **Formulare** erzwingen konsistente Dateneingabe  
* **RDF-Wissensgraph** ermöglicht Austausch & LOD-Publikation



