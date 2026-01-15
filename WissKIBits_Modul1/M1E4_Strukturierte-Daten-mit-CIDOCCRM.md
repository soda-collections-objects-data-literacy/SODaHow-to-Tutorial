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

Einheit 4: **Strukturierte Daten mit CIDOC CRM**  

**Dauer:** ~ 15 Min.

Lernziele:

* Ontologie zur Beschreibung von Ressourcen bennen, erläutern, anwenden. (LZ-ID 03_007_0778, 03_007_0779, 03_007_0780)
* Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa_03_007_0784a)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa_03_007_0780a)
* Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa_03_007_0805)



---

## Warum verwenden wir Ontologien?

Bei der Modellierung von Forschungsdaten aus den Geistes- und Kulturwissenschaften – geht es nicht nur darum, Daten zu beschreiben.

Ontologien helfen dabei:

* **Semantische Beziehungen auszudrücken**
* **Wissen maschinenlesbar zu machen**
* **Interoperabilität zwischen Einrichtungen und Systemen sicherzustellen**
* **Daten mit dem Linked Open Data-Ökosystem zu verbinden**
* **Kontext und Provenienz zu erhalten**.

---

## Was ist CIDOC CRM?

[CIDOC CRM](https://cidoc-crm.org/) ist eine **ISO-zertifizierte Ontologie (ISO 21127)**, entwickelt vom **CIDOC-Komitee der ICOM (International Council of Museums)**.

Sie wurde speziell für die **Dokumentation kulturellen Erbes** entwickelt und konzentriert sich auf:

* Ereignisse  
* Personen  
* Objekte  
* Orte  
* Zeiträume  
* und deren **semantische Beziehungen**

**Kurz gesagt:**  

CIDOC CRM bietet einen **gemeinsamen konzeptuellen Rahmen**, um kulturelle Informationen **verständlich und interoperabel** zu beschreiben.

WissKI verwendet die **CIDOC CRM OWL-Ontologie** als Grundlage, kann jedoch **zusätzliche Ontologien einbinden**.

---

## Zentrale Konzepte in CIDOC CRM

CIDOC CRM ist **ereigniszentriert**, d.h. es beschreibt nicht nur, *was etwas ist*, sondern **was mit ihm passiert**.

| Dimension          | Beispielklasse             | Bedeutung                                |
|-------------------|----------------------------|-------------------------------------------|
| Ding              | **E70 Thing**              | Physisches oder immaterielles Objekt      |
| Physisches Objekt | **E22 Human-Made Object**  | Artefakt, Exponat, Sammlungsobjekt        |
| Akteur            | **E21 Person**, **E74 Group** | Individuum oder Organisation           |
| Ereignis          | **E5 Event**               | Eine Handlung oder Veränderung            |
| Ort               | **E53 Place**              | Räumlicher Kontext                         |
| Zeit              | **E52 Time-Span**          | Zeitlicher Rahmen                          |

---

## Klassenhierarchie und Scope Notes

Die **Scope Note** einer CIDOC CRM-Klasse legt fest:

* **Was sie ausdrückt**
* **Welche Bedeutung und Grenzen sie hat**
* **Wann sie verwendet werden sollte**

Nicht entscheidend sind:

* der Name der Klasse,
* ihre hierarchische Position,
* oder intuitive Assoziationen.

**Scope Notes sind maßgeblich für die korrekte Modellierung.**

![Beispiel E39 Actor](../assets/E39Actor.jpg)

---

## Modellierungsstrategie im Tutorial

Es gibt verschiedene Ansätze, Domänenontologien zu erweitern:

* Neue **Subklassen** bilden
* Neue **Eigenschaften** definieren
* **Reine Wiederverwendung** bestehender CIDOC CRM-Klassen und -Eigenschaften
* **Kombinationen** der oben genannten Strategien

In diesem Tutorial wird eine **leichtgewichtige Erweiterungsstrategie** empfohlen:

→ **Domänenspezifische Unterklassen, wenn erforderlich**  
→ **Eigenschaften werden weitestgehend aus CIDOC CRM übernommen**

Das garantiert **Interoperabilität und CIDOC-Kompatibilität** und reduziert die Komplexität.

---

## Bedeutung ausdrücken mit CIDOC CRM

**Beispiel: Zelda-Spiel (SNES)**

*Das Videospiel „The Legend of Zelda: A Link to the Past“ wurde 1991 von Nintendo in Japan produziert.*



| Natürliche Aussage | CIDOC CRM-Repräsentation |
|--------------------|--------------------------|
| Das Spiel ist ein Objekt | **E22 Human-Made Object** |
| Titel: *The Legend of Zelda: A Link to the Past* | **E22** → *has title* → **E35 Title** |
| Es wurde hergestellt | **E65 Creation** |
| Hersteller ist Nintendo | **E65 Creation** → *carried out by* → **E74 Group (Nintendo)** |
| Produktionsort ist Kyoto | *took place at* → **E53 Place (Kyoto)** |
| Jahr: 1991 | *has time-span* → **E52 Time-Span (1991)** |

---

### Beispiel: Vase

| Natürliche Beschreibung | CIDOC CRM Repräsentation |
|-------------------------|--------------------------|
| Die Vase ist ein Artefakt | **E22 Human-Made Object** |
| Sie wurde in einer Ausgrabung gefunden | **E5 Event** (Excavation) |
| Das Team führte die Grabung durch | *carried out by* → **E74 Group** |
| Die Grabung fand in Nara statt | *took place at* → **E53 Place** |
| Jahr: 2005 | *has time-span* → **E52 Time-Span** |

---

## Top-Level- vs. Domänenontologien

| Top-Level Ontologie (Grundstruktur) | Domänenontologie (Fachspezifik) |
|------------------------------------|---------------------------------|
| z. B. **CIDOC CRM** | Erweiterungen wie MEGA, WissKI-Profile etc. |
| Definiert grundlegende Kategorien | Beschreibt disziplinäre Detailkonzepte |
| sorgt für Interoperabilität | erhöht Präzision |
| langfristig stabil | anpassbar an Forschungsbedarfe |

Eine **zweistufige Modellierungsstrategie** unterstützt:

* Semantische Klarheit
* Interoperabilität
* Erweiterbarkeit
* Nachhaltigkeit

---

## Relevanz und Nutzen von CIDOC CRM 

WissKI nutzt CIDOC CRM, weil es …

* **eindeutige, maschinenlesbare Bedeutungen** schafft
* **Begriffsmehrdeutigkeit und Datenisolierung** vermeidet
* **institutionenübergreifende Interoperabilität** ermöglicht
* **Ereignisse, Prozesse und Provenienz** systematisch abbildet
* **FAIR & Linked Open Data** unterstützt
* **robustes Fundament** für Wissensgraphen bietet 
* sich vollständig in den **WissKI Pathbuilder** integrieren lässt.


